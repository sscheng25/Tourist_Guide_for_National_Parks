---
title: "Information and Surroundings of the National Parks"
date: 2021-12-15
published: true
tags: [dataviz, folium, altair, hvplot, holoviews]
excerpt: "Giving a general sense of the local counties."
altair-loader:
  altair-chart-1: "charts/barplot1_altair.json"
  altair-chart-2: "charts/barplot2_altair.json"
  altair-chart-3: "charts/barplot3_altair.json"
hv-loader:
  hv-chart-1: ["charts/panelcensus.html", "800"] 
  hv-chart-2: ["charts/weather_panel.html", "600"] 
  hv-chart-3: ["charts/precipitation_panel.html", "600"] 
  hv-chart-4: ["charts/wind_panel.html", "600"] 
  hv-chart-5: ["charts/amenity_panel.html", "600"] 
toc: true
toc_sticky: true
---

In this part, we analyze the features in the counties where the top 10 national parks locate. We aim to give more local information to travelers who are planning to visit these parks.

## Local Crime cases

Safety is always of the highest priority when making travel decisions. We collect crime data from 2016 to 2020 and calculate the crime cases per 1,000 population in local counties. The average crime cases per 1,000 population is about 12, and the Katmai National Park has the largest crime numbers nearby.

<div id="altair-chart-1"></div>

## Local Amenities

When visiting a new place, travelers often have problem finding **parking spaces** and **restaurant**. We gather parking and restaurant data from Open Street Map database and want to give a general sense of these amenities for our users.

<div id="altair-chart-2"></div>

<div id="altair-chart-3"></div>

![park_and_county]({{ site.url }}{{ site.baseurl }}/assets/images/park_and_county.png)

***Interact with the selectors and see the distribution of amenities.***

<div id="hv-chart-5"></div>

## Median Household Income

There is a relationship between the income of local households and the regional level of services. We plot the median household income with a spatial unit of census block groups near the national parks. **Users can select their park of interest with the selector and enjoy the help of the interactive map.**

<div id="hv-chart-1"></div>

## Weather Data

It's also important to take a look at the local weather data, especially the temperature and precipitation. Here is the corresponding relationship of national parks and weather stations.

![park_and_station]({{ site.url }}{{ site.baseurl }}/assets/images/park_and_station.png)

***Use the selectors and see the weather data of each stations!***

<div id="hv-chart-2"></div>

<div id="hv-chart-3"></div>

<div id="hv-chart-4"></div>
