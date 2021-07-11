# Indego Data Analysis
 
Allison Zhang and Henry Chen

## What is Indego?
Indego, Philadelphia’s bike-share program, offers 24-hour, 30-day, and yearly pass options to ride one of the hundreds of bright blue bicycles, and white electric-assist bicycles stationed at more than 140 stations around the city. In this project, we will analyze 4 quarters of Indego data during the 2020 year. You can find more information about Indego on its site https://www.rideindego.com/.

## Installation

To run this program, simply click on the following Google Colab link: [here](https://colab.research.google.com/drive/1ESVHj9f0GdFCYeRsuuFas9kWAvcUjUNH?usp=sharing). Then go to Runtime -> Run All

To run this program on your local machine, make sure you have python3 and [jupyter](https://jupyter.org/install) installed.  

Download the above Colab notebook as a .py file and upload it to your jupyter notebook. You need to install plotly-express, pandas, and [MATLAB](https://www.mathworks.com/help/matlab/matlab_external/install-the-matlab-engine-for-python.html):
```
pip3 install plotly-express
pip3 install pandas
```
We recommend using Colab since the graphs and plots can be easily viewed in your browser.

## Code structure

The program first gets all the data from 2020 which can be found [here](https://www.rideindego.com/about/data/). Based on 2020 alone, we gathered and plotted data regarding people's preferences/tendencies using Indego, such as the average bike duration, electric vs. standard bike usage, most popular bike stations, etc.

Feel free to zoom in/out on the maps! You can also hover over the dots to get the station number, latitude, and longitude.

We then computed the approximate distance (in kilometers) between the most popular bike stations (using the [Haversine formula](https://en.wikipedia.org/wiki/Haversine_formula)) to visualize how far the most popular stations are from each other.

## Video Demo
https://drive.google.com/file/d/1651wL2OxOlCRtzR6DmRJoNKy_qXS1TFE/view?usp=sharing

Enjoy!
