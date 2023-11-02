## Intermediate Output

Here are some plots from my 2nd-year project which studies **the effect of water pollution on beverage manufacturers' entry decisions**. The sample period is from 2006 to 2019. The project is still in progress, so the results shown here are subject to change.

</br>

### Data Sources: 
- Dissolved oxygen (DO) readings from [Water Quality Portal](https://www.waterqualitydata.us/)
- Firm location from Data Axle, accessed through [Wharton Research Data Services](https://wrds-www.wharton.upenn.edu/pages/about/data-vendors/infogroup/)
- Clean Water State Revolving Fund (CWSRF) annual allotments from [EPA](https://www.epa.gov/cwsrf/clean-water-state-revolving-fund-cwsrf-allotments-federal-funds-states) 
- Demographics from American Community Surveys, accessed through [IPUMS](https://www.ipums.org/)
- Stream network and flow direction from [USGS NHDPlusV2](https://www.usgs.gov/national-hydrography/nhdplus-high-resolution)
- Weather from [PRISM Annual Normals (M4)](https://prism.oregonstate.edu/normals/)

</br>

### Descriptive Statistics:
At annual, county level:

1. Average DO Concentrations
![map_ave_do](https://github.com/ytyeh/foss-capstone/assets/133822845/51a0c824-b557-4928-bb31-63f2f9be5fdb)
 
2. Average Net Entry of Beverage Manufacturers
![map_ave_net_bus](https://github.com/ytyeh/foss-capstone/assets/133822845/e4b7f3a4-ade0-402f-a332-8307d047e329)

</br>

### Preliminary Result:
Using upstream state's past CWSRF allotment as an instrument for the downstream, adjacent county's DO readings, I found that **firms are more likely to locate at places with cleaner water**. The plot below shows the first-stage estimates with different lags and leads: 

![first_stage_95ci_mgl](https://github.com/ytyeh/foss-capstone/assets/133822845/8f518d66-014b-4bfc-bb94-a89f5e3e2b40)

