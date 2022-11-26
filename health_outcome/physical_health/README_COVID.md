
# COVID-19 Data

This data is collected from [The official UK government website for data and insights on coronavirus (COVID-19)](https://coronavirus.data.gov.uk/), which is the offical release of COVID-19 cases & vaccination data.

We collect the MSOA level data, which is the finest spatial level available for whole timeline.

We collect data from **2020-03-28** to **2022-08-31**, containing the following measures, and the meaning of the metrics are available on https://coronavirus.data.gov.uk/metrics

| Measure | Explanation |
| ------ | ------ | 
| newCasesBySpecimenDateRollingSum  |The number of new cases within rolling 7-day periods. Data are shown by the date the sample was taken from the person being tested. Data for the most recent days are considered incomplete as it takes time for tests to have an outcome and be recorded on relevant lab systems.|


Using the following links to directly download the data:

https://api.coronavirus.data.gov.uk/v2/data?areaType=msoa&metric=newCasesBySpecimenDateRollingSum&format=csv
