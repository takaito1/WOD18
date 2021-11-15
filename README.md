# Dissolved oxygen analysis
## World Ocean Database 2018
## BGC Argo
(1) Downloading BGC-ARGO data from ARGO GDAC repository, [python script](https://github.com/takaito1/WOD18/blob/master/python_scripts/search_bgcargo.ipynb)

(2) O2 profile check: read DOXY_ADJUSTED data and its QC flags. Identify "good" O2 data. Co-locate WOA2009 climatology and save them together as .nc file [python secipt](https://github.com/takaito1/WOD18/blob/master/python_scripts/bgcargo_check_WOA.ipynb)*

*This script needs WOA2009 dissolved oxygen climatology files. Download both annual and monthly. Create and store them in WOA09 folder [annual](http://data.nodc.noaa.gov/thredds/fileServer/woa/WOA09/NetCDFdata/dissolved_oxygen_annual_1deg.nc), [monthly](http://data.nodc.noaa.gov/thredds/fileServer/woa/WOA09/NetCDFdata/dissolved_oxygen_monthly_1deg.nc)

(3) Plot the match-up float O2 and WOA09 climatology [python script](https://github.com/takaito1/WOD18/blob/master/python_scripts/plot_selected_profiles.ipynb)

(4) Bin selected profiles and save statsitical means, standard deviations and sample size as .nc file, [python script](https://github.com/takaito1/WOD18/blob/master/python_scripts/Bin_selected_profiles.ipynb)
