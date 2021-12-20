---
title: "Cluster Analysis for National Parks"
date: 2021-12-14
published: true
tags: [dataviz, altair, hvplot, holoviews]
excerpt: "Clustering the national parks into 3 groups."
altair-loader:
  altair-chart-1: "charts/cluster_altair.json"
toc: true
toc_sticky: true
---

In this part, we will divide the top 10 national parks into 3 groups with *Hierarchical clustering* in `scipy.cluster.hierarchy` package. We hope to extract the similarities among each groups of parks and help travelers make a choice on which group to select.

## Cluster Results

- Group 0: Everglades National Park, Katmai National Park, Saguaro National Park
- Group 1: Crater Lake National Park, Grand Canyon National Park, Petrified Forest National Park, Great Smoky Mountains National Park, Mesa Verde National Park, Redwood National Park
- Group 2: Channel Islands National Park

## Matrix Plots

We plot some features used in clustering analysis above in the matrix plots below. For most features here, we can see a clustering pattern.

Parks in group 0 is common in high crime rate, many local restaurants, and moderate median household income. Group 1 has the similarity of low median household income, few local restaurants and other amenities, and moderate crime rate. Group 2 shows a high local income and low crime rate. 

<div id="altair-chart-1"></div>





