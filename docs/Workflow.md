---
layout: default
title: An Example Workflow
nav_order: 4
---

# An Example Workflow

Now that we've gotten an introduction to geocoding and web mapping, lets see how one might use it in practice.  Take this scenario: 
* You are a GIS analyst working with a non-profit in Toronto and you've been asked to put together a map highlighting the racial disparities in police violence at the hands of the Toronto Police.  The map needs to be interactive and compatible with mobile devices.  The non-profit has a limited budget, they can't afford an expensive ESRI license to use ArcMap Online.  Leaflet maps are the ideal solution here, they're free and effective.
* A dataset covering the years 2000-2017 is available with demographics data describing the victims.  However many incomplete records, the police refuse to release information identifying the victims in many cases.  The data also has the addresses where the incidents occurred.  To compensate for this, you decide to add census data to the map to show the demographics of the populations where the incidents are occurring.

This is how you might work thorough this task:


<a href="ExampleWorkflow.png" target="_blank">Open diagram in new tab</a>

<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="ExampleWorkflow.png" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>

Go back to your Jupyter Notebook window.
* Double click on "Example Workflow.ipynb" to open it.