# Strava Training Analysis
Strava is a social network of endurance athletes to connect, track and share progression in their fitness. I use the application to log my activities for training analysis and personal performance.

The purpose of this project was to explore my year in training using the Strava API to analyze the time I dedicated to training for the year for all of my logged runs, bikes and swims. I was able to view the following:

* Count of workouts by activity in 2020
* Longest activities in miles for the year
* Fastest workouts of the year by activity
* Total hours trained per month
* Total hours of training per week
* Average hours of training per week to date
* Average moving time per activity
* Hours of training during the week by day
* Time spent in heart rate zone
* Majority of activities in a particular heart rate zone
* Monthly intensity average relative to perceived effort and max heartrate
* Weekly intensity (current vs last week) - interactive
* Average heartrate and speed in mph - interactive
* Current week training log - interactive

## Technology Requirements 
* Altair
* Matplotlib
* Numpy
* Pandas
* Pygal
* Seaborn
* Stravaio
* Stravalib

## Instructions
* Install all required technologies in the requirements.txt file
* Retrieve API credentials from https://www.strava.com/settings/api and insert in config.py file
* Uncomment the code in the first cell and execute to retrieve the access_token
* Copy the access token from the output from the first cell execution and insert into the config.py file
* Copy and paste file path of your .svg file into your browser to interact with the weekly intensity and the current week training log data outputs 

![](hours_trained_per_month.JPG)

![](hours_trained_per_week.JPG)

![](hours_day_of_week.JPG)

![](heartrate_histogram.JPG)

![](intensity_average.JPG)

![](weekly_intensity.JPG)

![](current_week_training_log.JPG)

![](heartrate_type.JPG)
