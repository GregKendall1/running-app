
# Strava insights app 

This is an app which allows you to download your Strava data and provides insights to help you understand your performances. 

## Motivation
Strava is a popular app used to track different activities, mainly running and cycling. I use it a lot to track running and this app grew out of a desire to understand my training in more detail. In particular, I wanted to be able to view information about runs between any dates I want, in order to compare between e.g. different race builds. 

## Overview of features
I built this as a Streamlit app which allows the user to download their Strava data and then provides various insights. 
### Download data
- Walkthrough of how to use Strava API to download data

### Heart rate plots 
- User input of maximum heart rate to calculate zones
- User's choice of dates 
- Average time spent in each heart rate zone on a weekly basis
- Proportion of time spent in each zone overall

### Route map
- Plots all runs on an interactive map
- User can choose dates

### Running information
- Graphs of user's choice of data e.g. distance, speed, moving time
- Calendar heatmap of year to date
## Requirements
**Python Version**: 3.9.20 \
**Libraries**: pandas, numpy, folium, streamlit, matplotlib, urllib3, dayplot\
**Requirements**: *pip install -r requirements.txt*
