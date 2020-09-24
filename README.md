# BearMaps

BearMaps is a web mapping application inspired by google map and [OpenStreetMap](http://www.openstreetmap.org/). It is a course project of CS61B (Spring 2019) at UC Berkeley.

BearMaps has most of the basic features of a mapping application such as map rastering, zooming/dragging, location searching, routing and navigation. 

Try it yourself: [BearMaps online](http://bearmaps-candeng.herokuapp.com/map.html)

![](demo.gif)

Feature | Description
------- | -------
Map Rastering  | Finds the grid of images that best matches user's requested area and level of zoom. Then combines these images into one big image (rastered). 
Autocomplete and Search  | Provides search suggestions based on user input in the search bar and mark the search results with red dots on the map. A **Trie** backs this feature.
Routing  | Finds the shortest path between starting point and destination with **K-D Tree** and **A*** algorithm and plots navigation routes on the map.
Turn-by-turn Navigation  | Provides a sequence of navigation instructions such as "Turn left on University Avenue and continue for 1.0 miles".
