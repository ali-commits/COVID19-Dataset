# COVID19-Dataset

the complite hestorical cleaned COVID19 dataset

## Why New COVID-19 Dataset

> Automatically daily updates to add new cases.

> It contains the historical data of COVID-19 reports up to January 24th.

> It contains newly reported cases, newly reported deaths, newly reported recoveries, total reported cases, total reported deaths, total reported recoveries, currently active cases.

> It has been cleaned and compiled from different sources

## How To Use




The data is stored in four different places with four different forms

> 1.  in covid19_dataset.csv file which contains the whole dataset in one file

> 2.  in BY_REGION/ directory where the data has been split into different csv files based on countries and regions

> 3.  in BY_DAY/ directory where the data has been split into different csv files based on the date

> 4.  in BY_MEASUREMENT directory where the data has been split into different csv files based on the measurement (newly reported cases, newly reported deaths, newly reported recoveries, total reported cases, total reported deaths, total reported recoveries, currently active cases)

To use the data you can clone the repository

```bash
git clone https://github.com/newaaa41/COVID19-Dataset
```
or you can use the url for any csv file 
example
```
https://raw.githubusercontent.com/newaaa41/COVID19-Dataset/master/covid19_dataset.csv
```

## Sources:

> https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series

> https://www.worldometers.info/coronavirus/

> https://github.com/nytimes/covid-19-data

> https://github.com/ActiveConclusion/COVID19_mobility
