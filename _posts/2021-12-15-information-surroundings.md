---
title: "Information and surroundings of the National Parks"
date: 2021-12-15
published: true
tags: [dataviz, folium, altair, hvplot, holoviews]
excerpt: "Embedding interactive Folium charts on static pages using Jekyll."
altair-loader:
  altair-chart-1: "charts/barplot1_altair.json"
  altair-chart-2: "charts/barplot2_altair.json"
  altair-chart-3: "charts/barplot3_altair.json"
hv-loader:
  hv-chart-1: ["charts/panelcensus.html", "800"] # second argument is the height
toc: true
toc_sticky: true
---

This post will show examples of embedding interactive maps produced using [Folium](https://github.com/python-visualization/folium).

## OSMnx and Street Networks

The shortest route between the Art Museum and the Liberty Bell:

<div id="altair-chart-1"></div>

<div id="altair-chart-2"></div>

<div id="altair-chart-3"></div>

## Percentage of Households without Internet

<div id="hv-chart-1"></div>

See the [lecture 9B slides](https://musa-550-fall-2021.github.io/slides/lecture-9B.html) and the [lecture 10A slides](https://musa-550-fall-2021.github.io/slides/lecture-10A.html) for the code that produced these plots.
