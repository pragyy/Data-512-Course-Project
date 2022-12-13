# Data

This analysis research question will require several different datasets. The datasets are:

1. The RAW_us_confirmed_cases.csv file from the Kaggle repository of [John Hopkins University COVID-19 data](https://www.kaggle.com/datasets/antgoldbloom/covid19-data-from-john-hopkins-university). This data is updated daily. 
2. The CDC dataset of [masking mandates by county](https://data.cdc.gov/Policy-Surveillance/U-S-State-and-Territorial-Public-Mask-Mandates-Fro/62d6-pm5i). *Note that the CDC stopped collecting this policy information in September 2021.*
3. The New York Times [mask compliance survey data](https://github.com/nytimes/covid-19-data/tree/master/mask-use).

The majority of this data is by US County by Day. The mask compliance is a single shot estimator that gives you a compliance estimate for every County in the US. 

4. US Counties: COVID19 + Weather + Socio/Health data [Socioeconomic Time series dataset I](https://www.kaggle.com/datasets/johnjdavisiv/us-counties-covid19-weather-sociohealth-data?select=US_counties_COVID19_health_weather_data.csv)
5. US Counties: COVID19 + Weather + Socio/Health data [Socioeconomic Time series dataset II](https://www.kaggle.com/datasets/johnjdavisiv/us-counties-covid19-weather-sociohealth-data?select=us_county_sociohealth_data.csv)

The dataset contains county-level data on health, socioeconomics, and weather can help us address identify which populations are at risk for COVID19 and help prepare high-risk communities.

For this analysis, the focus is on the `Middlesex` country in the state of `Massachusetts`.

### Output Folder

This folder contains the intermediate files generated in the analysis.

The two files generated are - 
1. correlated features - This contains the variables that are correlated to the covid cases.
2. middlesex features - These are the constant attributes related to the Middlesex county.
