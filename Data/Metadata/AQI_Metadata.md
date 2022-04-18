# <Ukraine_Air_Quality Datasets>

## Summary

This dataset was prepared for Environmental Data Analytics (ENV 872L) at Duke University, Spring 2022. 

The data was analyzed in order to determine how the Russian invasion on Ukraine has impacted air quality in Ukraine.


## Investigators

Rachel Gordon, Shirley Fontanie, Julia Weinberg, Duke Nicholas School of the Environment, rachel.gordon@duke.edu, shirley.fontanie@duke.edu, julia.weinberg@duke.edu

## Keywords

Ukraine
Russia
Air Quality
PM2.5
PM10

## Database Information

The data was obtained through the World Air Quality Indices’ Air Quality Historical Data Platform in order to make air quality data more easily available to the general public. The data shows air quality values for a particular location over a 36-month time period. Data is not authenticated and is intended for research purposes only rather than official reporting. Data was collected on 4/3/22.


## Folder structure, file formats, and naming conventions 

Rawdata contains all imported, unsorted data. Processed data includes all data that has been wrangled throughout the analysis.


**PM25** any file that contains information only on PM2.5
**PM10** any file that contains information only on PM10
**LVIV** any file that contains only information on Lviv
**DNIPRO** any file that contains only information on Dnipro
**FULL** files that combine cities, air pollutants, year 

**Format** CSV

## Metadata

Data File Name | Column Name | Data Type
---------------| ------------|---------------
UkraineData | City | Factor (Dnipro and Lviv)
UkraineData | Date | Factor (later converted to date object)
UkraineData | pm25 | Integer (PM2.5 values)
UkraineData | pm10 | Integer (PM10 values)


