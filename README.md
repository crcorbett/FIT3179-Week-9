# FIT3179-Week-9
 
FIT3179 – Week 9 Homework Report

Domain:
•	Pedestrian traffic data
•	Impact of COVID-19 on pedestrian mobility in the City of Melbourne

Dataset:
•	Melbourne City – Pedestrian Counting System
•	Includes latitude/longitude for each sensor, counts number of pedestrians per hour at each sensor location
•	Dataset has been cleaned and manipulated using RStudio

Data transformation:
•	Each sensor has had their count rate normalised according to their min-max to allow for easier comparison between the two years. This was calculated according to the min-max pedestrian count recorded at each individual sensor site.
•	A point map has been used in this instance, as there are a number of pinpoint sensor locations. The relative intensity of pedestrian traffic at each sensor location is indicated by the colour scale.
