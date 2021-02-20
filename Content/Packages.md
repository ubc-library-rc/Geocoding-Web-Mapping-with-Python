---
layout: default
title: Basics of Python
nav_order: 2
---
# About Python:
* It's is a powerful programming language that is free to download and use.
* It's well suited for data analysis and visualization.
	* Making it a great choice for working with geospatial data!

# Accessing Python
* Today We'll be using a UBC server with python alread installed on it.
* If you want to install Python on your own computer, check out [Anaconda](https://www.anaconda.com/products/individual)
 	* Anaconda will install most commonly used python packages and set everything up for you.
 	* Anaconda won't install *every* package we're using today, but installing new packages is fairly straigtforward.

# Python Pakcakges:
 relies on a series of packages (aka libraries) to handle different tasks

* Packages are collections of code that are designed specifically for performing different tasks, e.g.: Plottoing, Statistics, Linear Algebra, etc.


## We'll be workng with the following packages today
* [numpy](https://numpy.org/doc/stable/)
	* Numpy is a powerful math libary for multidimensional data
* [pandas](https://pandas.pydata.org/docs/)
	* Pandas is a powerful library for handling data
* [geopandas](https://geopandas.org/)
	* This is a geospatial extension to pandas.  We'll use it to handle and manipulate our geospatial data
* [scipy](https://docs.scipy.org/doc/scipy/reference/)
	* Scipy is math library, we'll use it for calculating a linear regressions
* [matplotlib](https://matplotlib.org/contents.html)
	* Matplotlib is a powerful ploting library.  We'll uses it to make detailed maps and graphs
* [folium](https://python-visualization.github.io/folium/quickstart.html#Getting-Started)
	* Folium is a webmapping library that interaces with leaflet.js
* [branca](https://python-visualization.github.io/branca/colormap.html)
	* A package for creating colormaps
* [geopy](https://geopy.readthedocs.io/en/stable/)
	* This is a package that can connect us with different geodocing services




### Resources:

* If you're having issues with Python, a great place to check out is [Stack Overflow](https://stackoverflow.com/)
	* Its a popular forum where you can search, post, and answer coding questions.
* A related site that is more GIS focused site is [Stack Exchnage](https://gis.stackexchange.com/)