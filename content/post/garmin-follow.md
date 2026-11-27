+++
date = '2026-11-26T13:45:29-06:00'
draft = false
title = 'Building my own Strava Premieum Feature'
+++

Strava can cost money but USGS data is free.

# Creating my own Strava Premium Feature

	I am an avid runner. Ever since starting in August 2025, I have consistently ran 4-5 times a week. Doing this has greatly improved my overall fitness level and has allowed me to more easily focus on tasks and generate new project ideas. One of these ideas kept coming to be because Strava would simple not shut up about its subscription service. The only feature that I really eyed from this Premium tier was the 3D maps that could be generated. These were fun to watch, especially on other's long runs, to see how varied the terrain was and just get a sense of how far the run truly was. So, after some research, I realized I could just do it myself. 

### THE DATA
##### Garmin
	My current watch of choice is a Garmin Forerunner 165. For every activity, the watch generates a ".FIT" file that is uploaded to the Garmin Connect Service. This is downloadable through the online Garmin Connect Dashboard. Thankfully, there is a python library, fitdecode, that allows this file to be transfer to a variety of formats, any for my choosing really. 

##### Maps
	In the US, maps are easy. My friends in GIS may disagree, but I just have to download them.