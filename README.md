Script for a river animation of based on a given polygon chosing from 1984-2019 in Google Earth Engine (Javascript). 
This is an updated version based off of https://medium.com/google-earth/visualizing-changing-landscapes-with-google-earth-engine-b2d502dc02a8
The major change from the above is using the updated database and filtering out a year due to a system:timestart error for the year 2020. 

previous data: JRC Yearly Water Classification History, v1.1 [deprecated] (ee.ImageCollection("JRC/GSW1_1/YearlyHistory")
currnet data:  JRC Yearly Water Classification History, v1.3 (ee.ImageCollection("JRC/GSW1_3/YearlyHistory")

parameters to be adjusted based on desired output: frames per second (line 39) (higher frames per second will give a faster animation and connectedPixelCount(line 18) the higher the amount of connected pixels, the less outter waterbodies will be shown. 



