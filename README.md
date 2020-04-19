# Project: University of Washington, DATA 515 Spring 2020, Homework 1
# Title: Seattle Fremont Bridge Bicycle Counts
### Author: Bianca Zlavog
### Goal: Download hourly counts of bicycle crossings on the Fremont Bridge, process data, and produce a visualization for analysis
### License: This work is available under an MIT license, included in the repository
### Course website: http://uwseds.github.io/syllabus.html


## Inputs:

Data was gathered from the [City of Seattle Fremont Bridge Bicycle Counter](https://data.seattle.gov/Transportation/Fremont-Bridge-Hourly-Bicycle-Counts-by-Month-Octo/65db-xm6k). This contains the daily and hourly counts for bicycles crossing the bridge since the counter began operation in October 2012, through the most recent month. The counts are also split between which sidewalk the bicycles traverse, either the East or West sidewalk. The fields included in this data are:

-`Date`: date of the observation, in the format `MM/DD/YYYY HH:00:00 AM/PM`

-`Fremont Bridge Total`: total number of bikes that crossed the bridge

-`Fremont Bridge East Sidewalk`: number of bikes that crossed the bridge on the east sidewalk

-`Fremont Bridge West Sidewalk`: number of bikes that crossed the bridge on the west sidewalk

Date data was accessed: 04/11/2020


## Data processing:

1. In the first step, we download the raw data and save out a file to the repository.
2. In the second step, we process the data in a Pandas dataframe to prepare it for analysis. We add several new columns and subset the data to only one year.
3. In the last step, we produce a figure for analysis. We draw some conclusions about the trends in number of bicycles traversing the bridge by hour.


## Software used:

* MacOS Catalina 10.15.4
* Python 3.6.8
* ipython 7.13.0

