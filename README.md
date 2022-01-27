# wdbd-nltt5306

This collection of jupyter notebook and python scripts reduces and analyzes HST data of White Dwarf-Brown Dwarf Binary NLTT5306. 

Start with `reduction_NLTT5306.ipynb` to reduce all data and create fifty-four 1D spectra.

Proceed with `specanalysis.ipynb` when you are ready to analyze the data.

### 1. reduction_NLTT5306.ipynb

This jupyter notebook reduces data from a `/rawdata` folder. It starts by organizing the data into Orbits using the `organizingdata.py` script. The script, `organizingdata.py`, needs to be up-to-date as it uses a handmade dictionary of data structure to organize the data. 

This notebook will only reduce data one Orbit at a time. NLTT5306 has six orbits of data, so changing the `orbitnum` value at the beginning of the notebook isn't too time comsuming.

### 2. specanalysis.ipynb
