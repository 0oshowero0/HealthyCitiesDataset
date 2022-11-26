# Walkability Data

We adopt the walkability defination of recently proposed [Lancet paper](https://www.thelancet.com/journals/langlo/article/PIIS2214-109X(22)00072-9/fulltext), where the walkability is the averaged z score of population density, street intersection density and daily living score.

The population density is obtained through our population data and area data. The street inercection density is calculated through [OpenStreetMap](https://www.openstreetmap.org/) data, and the daily living score is calculated by the density of daily living POIs, which is defined as follows.

| NACIS Category | Description |
| ----------- |  ----------- |
| 4451 | Grocery Stores |
| 71219| Nature Parks and Other Similar Institutions|
| 481 | Air Transportation |
| 482 | Rail Transportation |
| 483 | Water Transportation |
| 485 | Transit and Ground Passenger Transportation |
