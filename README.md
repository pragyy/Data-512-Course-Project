# Data-512-Course-Project

During the last three years we all have been experiencing a global pandemic. This has been tragic and disruptive to many countries and has taken a deep personal toll on many individuals and their families. 

In this analysis, we are are understanding how did masking policies change the progression of confirmed COVID-19 cases from February 1, 2020 through October 1, 2021?

Apart from this, this analysis focuses on how the socioeconomic factors influenced the COVID-19.

## Codes and Resources Used

- Editor Used: VS code
- Python version: 3.9.4

## Python packages used

- Data manipulation: pandas, numpy, ruptures, datetime,
- Data Visualization: matplotlib, seaborn, statsmodel
- Miscelleneous: warnings

## Data Acquisition

This analysis research question will require several different datasets. The datasets are:

1. The RAW_us_confirmed_cases.csv file from the Kaggle repository of [John Hopkins University COVID-19 data](https://www.kaggle.com/datasets/antgoldbloom/covid19-data-from-john-hopkins-university). This data is updated daily. 
2. The CDC dataset of [masking mandates by county](https://data.cdc.gov/Policy-Surveillance/U-S-State-and-Territorial-Public-Mask-Mandates-Fro/62d6-pm5i). *Note that the CDC stopped collecting this policy information in September 2021.*
3. The New York Times [mask compliance survey data](https://github.com/nytimes/covid-19-data/tree/master/mask-use).

The majority of this data is by US County by Day. The mask compliance is a single shot estimator that gives you a compliance estimate for every County in the US. 

4. US Counties: COVID19 + Weather + Socio/Health data [Socioeconomic Time series dataset I](https://www.kaggle.com/datasets/johnjdavisiv/us-counties-covid19-weather-sociohealth-data?select=US_counties_COVID19_health_weather_data.csv)
5. US Counties: COVID19 + Weather + Socio/Health data [Socioeconomic Time series dataset II](https://www.kaggle.com/datasets/johnjdavisiv/us-counties-covid19-weather-sociohealth-data?select=us_county_sociohealth_data.csv)

The dataset contains county-level data on health, socioeconomics, and weather can help us address identify which populations are at risk for COVID19 and help prepare high-risk communities.

For this analysis, the focus is on the `Middlesex` country in the state of `Massachusetts`.

## Visuals

![img1](https://github.com/pragyy/Data-512-Course-Project/blob/main/pic/dailycovidcases.PNG)

![img2](https://github.com/pragyy/Data-512-Course-Project/blob/main/pic/changeincovidcases.PNG)

## License

Source Dataset License: [CCO Public Domain](https://creativecommons.org/publicdomain/zero/1.0/) and [Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
