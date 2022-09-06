# HousingDataVisuals

San Francisco housing data is cleaned using Python and Pandas and visualized in multiple ways using Hvplot and Geoviews. This assignment was done under Norhtwestern Fintech Bootcamp.

## Getting Started

This project was done on a Jupyter notebook, which means there is no need to run this as an "app". A Jupyter notebook contains python code and displays the results of the code on the same page when running on a local computer with all dependencies installed. But no need to install libraries. Just open up the ".ipynb" file in the repository and it shows the Python code with its immediate results. If the rendering of graphs is problematic (sometimes github does this), then open the PDF file named "san_francisco_housing.pdf", which shows all plots.

If actually running the jupyter notebook is desired, then install all necessary libraries with "pip install 'x'" where 'x' is:

- pandas
- panel
- hvplot
- Path

## Project Overview

This project analyzes San Francisco housing data from 2010 to 2016. Data is first pulled from .csv files from the Resources folder and cleaned. Some of the data is combined. Then the data can be plotted to compare trends on average rentals vs. average price per square foot when it comes to sales:

![San Francisco Rent vs. Price per sqft](bokeh_plot (1).png)

The same variables can be plotted for each neighborhood by using the "groupby" function:

![San Francisco Rent vs. Price per sqft in Each Neighborhood](bokeh_plot (3).png)

It is clear from these plots that rents have been rising faster than the price of homes.

In addition, using GeoViews, one can also put these data in a map and see it geographically per neighborhood:

![San Francisco Housing Map](bokeh_plot (2).png) 

All of these data can come in handy when deciding which neighborhoods to invest in and the type of investments that are most profitable.

