# Code and data for a Crash Course in Data Handling with R

This repository contains instructions and example data for an introductory workshop in data handling using R.  This material was prepared by Willson Gaul, Jon Yearsley, and Adam Kane.


Information about the example data:

**traffic.csv** Shows the number of vehicles and pedestrians passing my flat in Terenure, Co. Dublin, Ireland during the first COVID-19 lockdown. I counted the number of vehicles and pedestrians that passed during 5 minute intervals.  I did a 5 minute survey once per hour on many different days.  Each row is a 5-minute survey period.  The columns are:
date_ddmmyyyy - the date of the observation
time_hhmm - the time of day of the start of the survey (surveys lasted 5 minutes after the start time in this column)
vehicles - the number of motor-powered vehicles that passed during the 5 minutes (cars, busses, etc).
pedestrians - the number of walkers, runners, and bikers who passed during the 5 minutes.
notes - a column for incidental notes.


**plant.txt** - I think this is fabricated data - I think I generated the "height" numbers in R by drawing from normal distributions with different means for the different "treatment" groups.  But I'm not entirely certain about that.  The data could be described as a greenhouse experiment in which some plants are given normal water, and others are given less water as a "drought" treatment.  The outcome measure is how tall the plants are at the end of the experiment.  


**UCD_tufted_ducks.csv** - This shows the number of Tufted Ducks detected at different locations on UCD Belfield campus in Co. Dublin, Ireland.  These data were collected and submitted to eBird by me (W. Gaul), Ellie Roark, and Casey Patmore.  This is a simplified version of the data.  The full data, including additional covariates for survey effort and information about other species can be downloaded from eBird.org 
The columns are:
Location - the name of the location on UCD campus where the survey was conducted.
Date - the date of the observation
Protocol - the survey method, using eBird protocols
Tufted_Duck_count - the number of Tufted Ducks counted during the survey
