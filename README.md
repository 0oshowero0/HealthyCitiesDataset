# Healthy Cities: A Comprehensive Dataset of Environmental Determinants of Health in England Cities

## Introduction

This repo is the corresponding dataset discribed in Healthy Cities: A Comprehensive Dataset of Environmental Determinants of Health in England Cities.

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
│   │   │   ├── rooad_density
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
| Key | Specefic data identifier of the record. For dataset with more than three levels, it is used to depict specific category of the data (such as `WindSpeed` under `Weather` dataset). For dataset with different aggregation method or specifications, it depicts these side information (such as `Mean` for `HousePrice` and `Female` for `LifeExpectancy`) | ActualCost, Population, WindSpeed, PM2.5, Mean
| Value | Value of the data record.| 

