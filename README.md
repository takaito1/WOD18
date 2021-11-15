# Dissolved oxygen analysis
## World Ocean Database 2018
## BGC Argo
(1) Downloading BGC-ARGO data from ARGO GDAC repository, [python script](https://github.com/takaito1/WOD18/blob/master/python_scripts/search_bgcargo.ipynb)

(2) O2 profile check: read DOXY_ADJUSTED data and its QC flags. Identify "good" O2 data. Co-locate WOA2009 climatology and save them together as .nc file [python secipt](https://github.com/takaito1/WOD18/blob/master/python_scripts/bgcargo_check_WOA.ipynb)

(3) Plot the match-up float O2 and WOA09 climatology [python script](https://github.com/takaito1/WOD18/blob/master/python_scripts/plot_selected_profiles.ipynb)

(4) Bin selected profiles [python script](https://github.com/takaito1/WOD18/blob/master/python_scripts/Bin_selected_profiles.ipynb)

