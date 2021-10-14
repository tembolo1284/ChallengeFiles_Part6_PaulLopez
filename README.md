# Project Title
This application is the San Francisco housing market analyzer for challenge 6!  I begin the analysis by importing
a csv file with housing info that gives sales price by square foot, housing, units, and the gross rent by neighborhood and by year.
I slice the data by grouping the data by year and running a mean function.  I then plot the housing units by year
and analyze the housing unit trend in San Francisco over the 6 year period from 2010-2016.

The second part of the analysis has me do a similar slicing of the data to be able to view the average sale price per square foot
and comparing it to the gross rent. I plot both of these numbers together versus the year and do some analysis on that.
The second piece of this part has me group the data and plot the average sale price per square foot by neighborhood where I create a plot that allows the user to have a dropdown and select a neighborhood of their choice to view.

The final part of the housing market analyzer has me import longitude and latitude info on the neighborhoods and combine it
with the first file I imported. I then create an interactive map where one can see which neighborhoods have the highest gross rent and
highest sale price per square foot.





## Story

A Jupyter notebook that contains your analysis of the housing rental market data for San Francisco. The analysis will be complete with professionally styled and formatted interactive visualizations.

---

## Technologies

I am using python version 3.7.10 and am importing the following from the built-in libraries and from functions i've created myself:
import pandas as pd
import hvplot.pandas
from pathlib import Path

---

## Installation Guide

I have python version 3.7.10 and git version 2.33.0.windows.2 installed on a laptop running windows 10 pro.

I launch jupyter lab from the gitbash terminal and then run the risk_return_analysis noteback from the 
webpage that launches.


---

## Usage

Ensure the CSV files are in the resource folder, and then run the code. The user can pick different years and neighborhoods to look
at if they so choose.

That's it!


---

## Contributors
Just me, Paul Lopez.


---

## License
No licenses required. Just install everything for free, pull from my repository, and enjoy!
