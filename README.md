# Healthy Cities: A Comprehensive Dataset of Environmental Determinants of Health in England Cities

## Introduction

This repo is the code for generating the dataset discribed in Nature Scientific Data paper: [Healthy Cities, A comprehensive dataset for environmental determinants of health in England cities](https://www.nature.com/articles/s41597-023-02060-y).

## Folder Structure
```none
├── HealthyCitiesDataset
│   ├── environmental_determinants
│   │   ├── basic_statistics 
│   │   │   ├── area
│   │   │   ├── population
│   │   │   ├── boundary
│   │   │   ├── centroid
│   │   ├── health_related_behaviour_environment
│   │   ├── built_environment
│   │   │   ├── house_price
│   │   │   ├── building_density
│   │   │   ├── road_density
│   │   │   ├── street_view_features
│   │   │   ├── walkability
│   │   ├── natural_environment
│   │   │   ├── air_quality
│   │   │   ├── weather
│   ├── health_outcome
│   │   ├── physical_health
│   │   │   ├── asthma
│   │   │   ├── cancer
│   │   │   ├── dementia
│   │   │   ├── diabetes
│   │   │   ├── hyperlipidemia
│   │   │   ├── hypertension
│   │   │   ├── obesity
│   │   │   ├── covid_data
│   │   ├── mental_health
│   │   ├── life_expectancy
```

## Additional Information
For each subsection of the data, we provide detailed README file and metadata in corresponding folder.

We also provide a comprehensive data table that contains all the subsections in `all_data.csv.zip` (Please uncompress it first). The subsecitons are organized into a long table format with columns as follows:
| Column Name | Description | Example |
| ------ | -----------|-----------|
| TopCategory| The top category of the dataset.| HealthOutcome, EnvironmentalDeterminants|
| SecondCategory |The second category of the dataset.| PhysicalHealth, MentalHealth, LifeExpectancy, NaturalEnvironment, BehaviourEnvironment, BuiltEnvironment, BasicStatistics|
| ThirdCategory | The third category of the dataset.| DementiaExpenditure, Weather, TobaccoAvailability, RoadDensity, Population |
| CityCode | Exclusive ID for each city. | J01000007|
| CityName | Name of the city. | Birmingham|
| MSOACode | Exclusive ID for each MSOA.| E02001834|
| MSOAName | Name of the MSOA. |Birmingham 008 |
| Time | Time of the data record. For those without timestamps, we fill `None` to this column.| 2019-01-01
| Key | Specifications of the record, such as  `Mean` for `HousePrice` and `Female` for `LifeExpectancy`) |  Mean, Female, PM2.5 |
| Value | Value of the data record.| |