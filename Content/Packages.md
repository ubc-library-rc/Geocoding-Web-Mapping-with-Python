---
layout: default
title: Python Packages
nav_order: 3
---
# Python relies on a series of packages (aka libraries) to handle different tasks

* Packages are collections of code that are designed specifically for performing different tasks, e.g.: Plottoing, Statistics, Linear Algebra, etc.

* This server has every package we need already installed on it.
  * If you want to install python on your own computer.  I recomemend you use check out: [Anaconda](https://www.anaconda.com/products/individual)
  * It will install most commonly used python packages and set everything up for you.

## We'll be workng with the following packages today
* [numpy](https://numpy.org/doc/stable/)
	* Numpy is a powerful math libary for multidimensional data
* [pandas](https://pandas.pydata.org/docs/)
	* Pandas is a powerful library for handling data
* [matplotlib](https://matplotlib.org/contents.html)
	* Matplotlib is a powerful ploting library.  We'll uses it to make detailed maps and graphs
* [follium](https://python-visualization.github.io/folium/quickstart.html#Getting-Started)
	* Scipy is math library, we'll use it for calculating a linear regression & chi sqare
* [geopy]https://geopy.readthedocs.io/en/stable/)
	* This is a package that can connect us with different geodocing services

### Unfortunately Geopy isn't installed on this servere :(


### But we can intsll it ourselves!

* Following the same procedure as the Setup page, open a new terminal

  * In the terminal window type:
    pip install geopy

  * Then hit enter

* This will install the geopy package.  We'll use this package to do our Geocoding
