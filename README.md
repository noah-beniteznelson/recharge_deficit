## Code for "The Role of Vadose Zone Storage Deficits in Modulating Groundwater Recharge and Streamflow in Seasonally Dry Watersheds"

### Noah K. Benitez-Nelson, David N. Dralle, W. Jess Hahm, Daniella M. Rempe

Dataset and code to replicate analyses in upcoming paper submission.

Last updated September 11th, 2024 by Noah Benitez-Nelson.

**Code Descriptions**
- *PART_I.ipynb*:  Extract catchment hydrology, clean data, filter watersheds, calculate the root-zone storage deficit, estimate groundwater recharge, summarize catchment hydrogeology, determine the dependence of subsurface storage on winter precipitation. 
- *PART_II.ipynb*:  Analyses and figures.
- *hydrograph_recession_comparison.ipynb*:  Compare groundwater recharge estimation of Dralle et al. (2023) and method used herein.
- *recharge_ratio_resolution_comparison.ipynb*:  Compare how increasing the resolution of input data products affects the storm-event analysis. 
- *et_product_comparison.ipynb*:  Compare evapotranspiration products across basins.

**Data Descriptions**
- *extracted_catchment_data.csv*:  Contains precipitation, discharge, and evapotranspiration daily timeseries from basins included in analysis.
- *filtered_catchment_data.csv*:  Filtered basin fluxes with calculated recharge and root-zone storage deficit.
- *catchment_attributes.csv*:  Hydrogeology of catchments and results of sensitivity analysis.
