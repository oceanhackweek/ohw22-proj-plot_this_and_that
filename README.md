# The ultimate collection of plotting example notebooks (OHW22_proj_plot_this_and_that)
---

## One line description
Develop a collection of notebooks in Python and R to create ocean plots based on open source data.

---

### Collaborators
Australia OHW: Nick Mortimer, Yuhang Liu, Natalia Ribeiro, Leo Laiolo, Craig Steinberg, Tom Armstrong, Xinlong Liu, Denisse Fierro Arcos, Mussa Ngosha.  
Other OHW satellite events: Marine Lebrec, Gammon Koval, Liz Ferguson.

---

### Background/Motivation
To create scripts with plotting examples that are clear and easy to modify.  
Look at the Ocean current website and see the vast range of plots, these are all based on data that is available in the IMOS s3 bucket.

### Goals/Tasks
* Find plots from around the internet such [these](http://oceancurrent.imos.org.au/index.php).
* Identify data sources
* Build plots using xarray / Hvplot etc.
* Create intake catalogues to get the data.

### Datasets/Supporting Information
* [Data sets](http://imos-data.s3-website-ap-southeast-2.amazonaws.com/?prefix=IMOS/SRS/SST/ghrsst/L3S-1d/dn/) and [infrastructure support](http://imos-data.s3-website-ap-southeast-2.amazonaws.com/?prefix=IMOS/OceanCurrent/GSLA/NRT00/2022/)
* [Various scripts for our Python User Group](https://github.com/UNSW-MATH/python_group
https://github.com/aodn/imos-user-code-library)
* [R scripts on how to access EDRDAPP data](https://github.com/virginiagarciaalonso/useR_2022_sst) - Slides and poster available in English and Spanish.
* [The Inter-Sectoral Impact Model Intercomparison Project (ISIMIP)](https://www.isimip.org/).

### Workflow
Existing methods:  
  
* [Loading ANFOG glider data, producing plots, saving outputs](https://github.com/UNSW-MATH/python_group/blob/master/code%202019/IMOS_load_ANFOG.ipynb).
* [GliderTools](https://glidertools.readthedocs.io/en/latest/cheatsheet.html) - A useful package for processing glider data, but built for EGO NetCDF files. Compatible with IMOS files with some extra code.
* [Data product tutorials](https://figshare.com/articles/software/Data_Product_tutorials_for_Roughan_et_al_Multi-decadal_ocean_temperature_time-series_and_climatologies_from_Australia_s_long-term_National_Reference_Stations_2022_/18232691?file=32991497).

### References
