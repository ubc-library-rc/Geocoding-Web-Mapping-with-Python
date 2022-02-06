---
layout: default
title: Geocoding & Web Maps
nav_order: 3
---

# Geocoding

The process of attributing coordinates (Latitude/Longitude) to descriptive locations (Street Address).  With Python, we can use a variety of web based services (google maps, mapbox, open street map, etc.) to perform geocoding.  We're using mapbox today because it strikes a good balance between cost and accuracy.  [Google maps](https://developers.google.com/maps/documentation/geocoding/overview) is arguably the best geocoding service, but it costs money :/ (5.00 USD per 1000 request).  [Open Street Maps](https://osmnames.org/) is totally free, but it is error prone. [Mapbox](https://docs.mapbox.com/api/search/geocoding/) is free, up to [100,000 requests per month](https://www.mapbox.com/pricing/#geocode) and gives fairly reliable results.  We will be using a module called [geopy](https://geopy.readthedocs.io/en/stable/) to interface with Mapbox for us.

## Using Mapbox

Create a free [Mapbox](https://mapbox.com) account.  Once you have an account, you will be given an [access token](https://account.mapbox.com/access-tokens/).  Which lets you use the mapbox service.  

# Web Mapping

Web mapping takes cartography beyond static maps.  Today, we'll use a Python package called [follium]http://python-visualization.github.io/folium/ which allows us to create dynamic, interactive webmaps that can be embedded in webpages.  Folium will "translate" our python commands into Javascrpt and create [leaflet](https://leafletjs.com/) maps.  Leaflet is a javascript package for creating beautifly functional webmaps.   Follium is already installed, so we don't have any more steps to do here!

# Getting Started with Geocoding

You can close the terminal window, we don't need it anymore.  Go back to your Jupyter Notebook window.
* Double click on "Geocoding and Webmapping.ipynb" to open it.

# An Example Workflow

Now that we've gotten an introduction to geocoding and web mapping, we'll work through a practical application by mapping violence at the hands of Police in BC.  Go back to your Jupyter Lab window, double click on "Example Workflow.ipynb" to open it.