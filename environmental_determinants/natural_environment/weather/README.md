
# Weather Data

This data is collected from [Met Office: HadUK-Grid](https://www.metoffice.gov.uk/research/climate/maps-and-data/data/haduk-grid/haduk-grid), which is a gridded climate observations for the UK.

Details for the dataset information can be found in these links:

https://catalogue.ceda.ac.uk/uuid/4dc8450d889a491ebb20e724debe2dfb

https://www.metoffice.gov.uk/research/climate/maps-and-data/data/haduk-grid/datasets


Specifically, we collect 12km x 12km grid level data for city level from  
https://catalogue.ceda.ac.uk/uuid/652cea3b8b4446f7bff73be0ce99ba0f

And 1km x 1km grid level data for MSOA level from
https://catalogue.ceda.ac.uk/uuid/bbca3267dc7d4219af484976734c9527


The selected variables as as follows:

| Variable ID| Variable Name | Description | Time Resolution |Unit |
| ------ | ----------- |  ----------- |  ----------- | ----------- |
| tasmin | Minimum air temperature| Minimum air temperature measured between 0900 UTC on day D-1 and 0900 UTC on day D  | Daily | degC | 
| tasmax | Maximum air temperature|  Maximum air temperature measured between 0900 UTC on day D and 0900 UTC on day D+1  | Daily | degC | 
| rainfall | Precipitation|Total precipitation amount measured between 0900 UTC on day D and 0900 on day D+1 | Daily | mm|
| hurs | Mean relative humidity|  Average of hourly (or 3-hourly) relative humidity over the month | Monthly | % |
| sun | Sunshine duration | Duration of bright sunshine during the month | Monthly | hours | 
|snowLying|Days of snow lying|Count of days with greater than 50% of the ground covered by snow at 0900 UTC | Monthly | days |
| sfcWind | Mean wind speed at 10 m | Average of hourly mean wind speed at a height of 10 m above ground level over the month, season or year | Monthly | knots |


