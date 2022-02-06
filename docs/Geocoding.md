---
layout: default
title: Geocoding and Making Web Maps with Python
nav_order: 3
---

# Geocoding and Making Web Maps with Python
{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>


# Why Python?

Its a great language! But its not the only language. Just as English, Cantonese, or Punjabi could all be used to explain systemic racism; Python, Javascirpt, or R can all be used to quantify and visualize the scale of the problem.  I like python because its very flexible, fairly easy to read / write, well suited for data analysis, has lots of packages for GIS, and it's completely free!

**Packages**: Python has a number of built in functions, but many of the most useful tools and functions come require us to [import](https://docs.python.org/3/reference/simple_stmts.html#import) packages.

* Packages are pre-written blocks of code, sometimes referred to as libraries.
* They are built for addressing specific tasks: e.g. linear algebra, mapping, plotting.


# Geocoding

The process of attributing coordinates (Latitude/Longitude) to descriptive locations (Street Address).  With Python, we can use a variety of web based services (Google Maps, Mapbox, Open Street Maps, etc.) to perform geocoding.  We're using Mapbox today because it strikes a good balance between cost and accuracy.  [Google maps](https://developers.google.com/maps/documentation/geocoding/overview) is arguably the best geocoding service, but it costs money :/ (5.00 USD per 1000 request).  [Open Street Maps](https://osmnames.org/) is totally free, but it is error prone. [Mapbox](https://docs.mapbox.com/api/search/geocoding/) is free, up to [100,000 requests per month](https://www.mapbox.com/pricing/#geocode) and gives fairly reliable results.  We will be using a module called [Geopy](https://geopy.readthedocs.io/en/stable/) to interface with Mapbox for us.

**Using Mapbox**: Create a free [Mapbox](https://mapbox.com) account.  Once you have an account, you will be given an [access token](https://account.mapbox.com/access-tokens/).  Which lets you use the Mapbox service.  

# Web Mapping

Web mapping takes cartography beyond static maps.  Today, we'll use a Python package called [follium](http://python-visualization.github.io/folium/) which allows us to create dynamic, interactive web maps that can be embedded in webpages.  Folium will "translate" our python commands into Javascrpt and create [leaflet](https://leafletjs.com/) maps.  Leaflet is a Javascript package for creating beautiful functional web maps.   Follium is already installed, so we don't have any more steps to do here!
