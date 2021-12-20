---
title: "Analysis on Air Ticket Price from PHL"
date: 2021-12-13
published: true
tags: [dataviz, altair, hvplot, holoviews]
excerpt: "Plotting the change of ticket price during Christmas this year."
altair-loader:
  altair-chart-1: "charts/air_ticket_Altair.json"
toc: false
---

To help travelers from Philadelphia plan their trip during Christmas this year, we collect the air ticket price data from [Southwest Airlines](https://www.southwest.com/) and [United Airlines](https://www.united.com/). We select **PHL** as the origin and the **nearest commercial airport of each national park** as the destination. The ticket price data was collected on Dec 6th, 2021 from their official website.

## Map and Plot of Air Ticket Price

Here we make an interactive map and line chart to show the change of air ticket price for Christmas holiday. The size of the circle on the map represents the mean air ticket price, and the line chart below plots the ticket price of two airlines. 

***Click on the circles on the map and see!***

<div id="altair-chart-1"></div>


