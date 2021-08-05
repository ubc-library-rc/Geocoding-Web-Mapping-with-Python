---
layout: default
title: Getting Started
nav_order: 2
---

# Why Python?

Its a great language! But its not the only language. Just as English, Cantonese, or Punjabi could all be used to explain systemic racism; Python, Javascirpt, or R can all be used to quantify and visualize the scale of the problem.   like python because its very flexible, fairly easy to read / write, well suited for data analysis, has lots of packages for GIS, and it's completely free!

## Accessing Python

Today We'll be using a UBC server with python already installed on it.  If you want to install Python on your own computer, check out [Anaconda](https://www.anaconda.com/products/individual).

* Anaconda will install most commonly used python packages and set everything up for you.
* Anaconda won't install *every* package we're using today, but installing new packages is fairly straightforward.

## Other Resources:

If you're having issues with Python, a great place to check out is [Stack Overflow](https://stackoverflow.com/).  It is a popular forum where you can search, post, and answer coding questions.
* A related site that is more GIS focused site is [Stack Exchange](https://gis.stackexchange.com/)


# Download the Code and Data

## 1) Start Python
* UBC provides server space where you can run Python using a [Jupyter Notebook](https://ubc.syzygy.ca/jupyter)
  * Login with your CWL.  You'll then be taken to a blank jupyter window.
* This is good option for getting your bearings because nearly everything is already set up.
  * You don't have to worry about installing anything on your own system.
* This may sound intimidating/confusing.  But don't worry, its easy.  You don't need to know command line to do this.  I'll walk you through step by step!!
  * You can refer to the video below for helps with steps 2 - 5. 


## 2) Open a terminal
* We're going to open a command terminal and use command line clone the Github workshop's repository.
* In they Jupyter window, click "New" in the top right and select "Terminal" from the dropdown menu.

## 3) Clone the repository
* In the new terminal window that opens, paste the command:

		git clone https://github.com/ubc-library-rc/Geocoding-Web-Mapping-with-Python/

* This tells Git (a file tracking software) to to download a repository for this workshop with all the files and code.
* Hit enter and the flies will download after a few seconds.


<a href="SetUp.mp4" target="_blank">Open Video in new tab</a>

<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="SetUp.mp4" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>




# Using a Jupyter Notebook

Go back to your Jupyter Notebook window.  **Don't** close the terminal window, we'll use it again later.  You will notice a folder titled "Geocoding and Webmapping with Python", double clicking the folder will open it.
* You'll see a two more folders and a collection of files.  
	* The .ipynb tag on the end denotes a Jupyter "Notebook"
* A Notebook is a collection of Python code and annotations that can be run interactively.
	* Double click on "Getting Started with Python.ipynb" to open it.