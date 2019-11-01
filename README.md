# Data visualization

Just a collection of python scripts for visualizing data.


# Barycentric legend

Given a pixel density and number of rows the script creates a triangular RGB legend based off
barycentric coordinates, useful when mapping trivariate data where variables always add to 1,
like [soil texture](https://en.wikipedia.org/wiki/Soil_texture).

## Script:
	barycentric_triangle_legend.py

## Requirements:
	- numpy
	- pycairo

10 Rows          | 25 Rows  | 50 rows
:-------------------------:|:-------------------------:|:-------------------------:
![](examples/triangle_200_10.png)  | ![](examples/triangle_200_25.png) | ![](examples/triangle_200_50.png)
