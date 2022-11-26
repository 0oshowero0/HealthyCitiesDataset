
# Air Quality Data

This data is collected from [UK AIR](https://uk-air.defra.gov.uk/data/), which is the offical release of air informaion organized by Department for Environment Food & Rural Affairs.

Here we focus on the AURN network：
> **AURN network**: The AURN is the UK's largest automatic monitoring network. It includes automatic air quality monitoring stations measuring oxides of nitrogen (NOx), sulphur dioxide (SO2), ozone (O3) and particles (PM10 and PM2.5). These sites provide high resolution hourly information which is communicated rapidly to the public, using a wide range of electronic, media and web platforms.

Details for the site location and information can be found by these tools:

https://uk-air.defra.gov.uk/networks/find-sites

https://uk-air.defra.gov.uk/interactive-map?network=UUNN

https://uk-air.defra.gov.uk/networks/search-site-info

We use _Get measured data and simple statistics_ data tool to collect data. Specifically, we select _Search Hourly Networks_, collect _Daily Mean_ records from **2019-01-01** to **2022-08-31**, and select _Nitrogen oxides as nitrogen dioxide (NOx in our data column)_, _PM2.5 particulate matter hourly measured (PM2.5 in our data column)_, and _PM10 particulate matter hourly measured (PM10 in our data column)_.

For cities with more than one site, we preserve the measures in each site. We provide the site name and note in metadata.csv.

The unit for data is V ugm-3.