# Point-of-Interest Data

This data is collected from [SafeGraph](https://docs.safegraph.com/docs/places), which contains 1,497,076 POIs in United Kindom. We filter the POIs in selected cites, resulting 211,398 entries.

The category of POIs is in 2017 version of the North American Industry Classification System (NAICS) developed by the US Census Bureau, which consists of a numeric NAICS code up to 6 digits in length. The defination is available in https://www.census.gov/naics/.

We calculate the availability by the number of specific POIs divided by the population. The selected POI categories are as follows:

| Type | NACIS Category | Description |
| ------ | ----------- |  ----------- |
| Alcohol   | 7224,4453,4451 | Dringking Places, Beer/Wine/Liquor Stores, Grocery Stores |
| Tobacco |  453991,4451 | Tobacco Stores, Grocery Stores|
| Health | 446, 621,622,623,|Health and Personal Care Stores, Ambulatory Health Care Services, Hospital, Nursing and Residential Care Facilities|
| Exercise | 71394, 71219| Fitness and Recreational Sports Centers,Nature Parks and Other Similar Institutions|