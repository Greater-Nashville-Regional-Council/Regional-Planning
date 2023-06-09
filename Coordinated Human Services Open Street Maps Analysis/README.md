# **Coordinated Human Services Plan Open Street Maps Analysis**

## *Table of Contents*  
+ Overview
+ Data   
+ Analysis  
+ Results  


## Overview  

Considerations for the Coordinated Human Services Plan include analysis of the MTA Access Rides. This is a service offered to low-income seniors in the region where on-demand rides from their location to a new location of choice are offered. This repository contains an analysis of the most common dropoff areas.

## Data   

Data is collected from proprietary pickup/dropoff points, building level establishment data is collected from Open Street Maps Overpass API, and shapefiles containing the top 5th, 10th, and 25th percentiles of dropoff locations aggregated by "walkable" hexagon areas are created using ArcMAP by GNRC staff and then imported here.  

## Analysis  

This Open Street Maps data is incomplete, but useful for getting an idea of the establishment makeup for high-volume dropoff areas. Because it is incomplete, this analysis is fairly light. Folium is used to create an interactive map where the user can turn on and off different layers showing a simple heat map, polygons of the top xth percentile of dropoff locations, and clustered establishment data. In addition, a list is produced of all establishments available through Open Street Maps that are located within the top 5th percentile of total aggregated dropoffs within a reasonably walkable hexagonal radius.  

## Results  

The clear hotspot for dropoffs is located around the Vanderbilt/Midtown hospital area, but beyond that without the establishment people are being dropped off at the analysis is relatively inconclusive.