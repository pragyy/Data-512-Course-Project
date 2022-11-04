# Data-512-Course-Project

During the last three years we all have been experiencing a global pandemic. This has been tragic and disruptive to many countries and has taken a deep personal toll on many individuals and their families. 

In this analysis, we are are understanding how did masking policies change the progression of confirmed COVID-19 cases from February 1, 2020 through October 1, 2021?

## Codes and Resources Used

- Editor Used: VS code
- Python version: 3.9.4

## Python packages used

- Data manipulation: pandas, numpy, ruptures
- Data Visualization: matplotlib, seaborn
- Miscelleneous: warnings

## Data Acquisition

This analysis research question will require several different datasets. The datasets are:

1. The RAW_us_confirmed_cases.csv file from the Kaggle repository of [John Hopkins University COVID-19 data](https://www.kaggle.com/datasets/antgoldbloom/covid19-data-from-john-hopkins-university). This data is updated daily. 
2. The CDC dataset of [masking mandates by county](https://data.cdc.gov/Policy-Surveillance/U-S-State-and-Territorial-Public-Mask-Mandates-Fro/62d6-pm5i). *Note that the CDC stopped collecting this policy information in September 2021.*
3. The New York Times [mask compliance survey data](https://github.com/nytimes/covid-19-data/tree/master/mask-use).

The majority of this data is by US County by Day. The mask compliance is a single shot estimator that gives you a compliance estimate for every County in the US. 

For this analysis, the focus is on the `Middlesex` country in the state of `Massachusetts`.

## Visuals

!(https://github.com/pragyy/Data-512-Course-Project/blob/main/pic/dailycovidcases.PNG)
!(https://github.com/pragyy/Data-512-Course-Project/blob/main/pic/changeincovidcases.PNG)
