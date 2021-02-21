---
layout: default
title: Getting Started
nav_order: 4
---

# Step 1) Start Python
### UBC provides server space where you can run Python using a [Jupyter Notebook](https://ubc.syzygy.ca/jupyter)
* This is good option for getting your bearings becasue nearly everything is already set up.
  * You don't have to worry about installing anything on your own system.
  * Login with your CWL.  You'll then be taken to a blank jupyter window.

# Step 2) Download the data & code
## Open a comand terminal and clone the Github workshop's repository.
* This may sound intimidating/confusing.  But don't worry, its easy.  You don't need to know comand line to do this.  I'll walk you through step by step!!
* You can refer to the video below for helps with steps 2 - 4. 

## A) In they Jupyter window, click "New" in the top right and select "Terminal" from the dropdown menu.

## B) In the new terminal window that opens, type the command "git clone" followed by this URL: https://github.com/ubc-library-rc/Geocoding-Web-Mapping-with-Python/
* "git clone" tells Git (a file tracking software) to to download a repository (the [URL](https://github.com/ubc-library-rc/Geocoding-Web-Mapping-with-Python/) is the location of the repository for this workshop with all the files and code

## C) Hit enter
* The flies will download after a few seconds.


# Setp 3) Installing geopy
## A) In the terminal window type:
    pip install geopy

## B) Hit enter
* This will install the geopy package. 

# Step 4) Navigating Jupyter Notebooks

## A) Close the terminal window.

## B) Go back to your Jupyter Notebook window
* You will notice a folder titled "Geocoding and Webmapping with Python"
  * Double clicking the folder will open it.
* You'll see a two more folders and a collection of files.  The .ipynb tag on the end denotes a Jupyter "Notebook"
  * A Notebook is a collection of Python code and Annotations that can be run interactively.

## C) Open Geocoding & Webmapping with Python.ipynb
* Navigate back to the window with your Mapbox API key
* Copy the key and paste it in the first code block where you see
  * api_key = ""

## D) You're ready to run the code!

<a href="git_Clone.mp4" target="_blank">Open Video in new tab</a>

<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="git_Clone.mp4" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>


