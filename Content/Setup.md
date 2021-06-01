---
layout: default
title: Getting Started
nav_order: 3
---

# Step 1) 
## Create a [Mapbox](https://mapbox.com) accont
  * We need this to access our API key later

# Step 2) Download the data & code
## A) Start Python
* UBC provides server space where you can run Python using a [Jupyter Notebook](https://ubc.syzygy.ca/jupyter)
  * Login with your CWL.  You'll then be taken to a blank jupyter window.
* This is good option for getting your bearings because nearly everything is already set up.
  * You don't have to worry about installing anything on your own system.
* This may sound intimidating/confusing.  But don't worry, its easy.  You don't need to know command line to do this.  I'll walk you through step by step!!
  * You can refer to the video below for helps with steps 2 - 5. 


## B) Open a terminal
* We're going to open a command terminal and use command line clone the Github workshop's repository.
* In they Jupyter window, click "New" in the top right and select "Terminal" from the dropdown menu.

## C) Clone the repository
* In the new terminal window that opens, paste the command:
  git clone https://github.com/ubc-library-rc/Geocoding-Web-Mapping-with-Python/
  * This tells Git (a file tracking software) to to download a repository for this workshop with all the files and code.
  * Hit enter and the flies will download after a few seconds.


# Setp 3) Installing geopy
## A) In the terminal window type:
    pip install geopy
* Hit enter to install the geopy package. 

# Step 4) Navigating Jupyter Notebooks
## Opening a notebook
* Close the terminal window. Go back to your Jupyter Notebook window
* You will notice a folder titled "Geocoding and Webmapping with Python", double clicking the folder will open it.
* You'll see a two more folders and a collection of files.  The .ipynb tag on the end denotes a Jupyter "Notebook"
  * A Notebook is a collection of Python code and Annotations that can be run interactively.
* Double click on "Geocoding & Webmapping with Python.ipynb" to open it.

# Step 5) Adding your API key

* You can get your [access token here](https://account.mapbox.com/access-tokens/)
* On this page, you should see a "Default Public Token".  This will be the key we use to access Mapbox's geocoding service
  * If not click the "Create Token Button"
    * Give it a name, leave all other default options checked, and click "Create Token".

* Copy the key and paste it in the first code block where you see
  * api_key = ""

### You're ready to run the code!


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


