---
layout: default
title: Basics of Python
nav_order: 2
---
# Python is:
* A powerful programming language that is free to download and use.
* Well suited for data analysis and visualization.
* A great choice for working with geospatial data!

# Accessing Python
* Today We'll be using a UBC server with python already installed on it.
* If you want to install Python on your own computer, check out [Anaconda](https://www.anaconda.com/products/individual)
 	* Anaconda will install most commonly used python packages and set everything up for you.
 	* Anaconda won't install *every* package we're using today, but installing new packages is fairly straightforward.

# Python Pakcakges:
* Packages (aka libraries) are collections of code that are designed specifically for performing different tasks, e.g.: Plotting, Statistics, Linear Algebra, etc.

## The main packages used in this workshop are:
* [Pandas](https://pandas.pydata.org/docs/) is a powerful library for handling tabular data.
	* We'll use Pandas to import, query, and manipulate data tables.
* [Geopandas](https://geopandas.org/) is a geospatial extension to pandas.
	* We'll use Geopandas to handle some of the spatial components of our data set
* [Matplotlib](https://matplotlib.org/contents.html) is a plotting library.
	*  We'll uses Maptlotlib to make plots and investigate relationships in the dateset.
* [Geopy](https://geopy.readthedocs.io/en/stable/) is a library that connect us with different geodocing services.
	* We'll use Geopy to request the coordinates (Latitude/Longitude) of addresses using Mapboxes geocdong API.
* [Folium](https://python-visualization.github.io/folium/quickstart.html#Getting-Started) is a library that "translates" Python commands to JavaScript and creates interactive webmaps
	* We'll use Folium to display the data on maps that we can interact with (click, pan, zoom).


# Other Resources:
* If you're having issues with Python, a great place to check out is [Stack Overflow](https://stackoverflow.com/)
	* Its a popular forum where you can search, post, and answer coding questions.
* A related site that is more GIS focused site is [Stack Exchnage](https://gis.stackexchange.com/)