---
title: "Tutorials"
description: "Find learning resources and tutorials for open source spatial analysis"
draft: false
layout: subsection
slug: tutorials
---

Note: tutorials are currently still under development, and more will be added in the upcoming year.

## R Spatial Workshop Notes - **new!**

Workshop notes and scripts from the R Spatial Workshop can be found at the [following link](https://spatialanalysis.github.io/workshop-notes/). Topics to be covered include spatial data manipulation, mapping, and interactive visualization. 

Please see our [Events](https://spatialanalysis.github.io/events/) page for more information about these workshops.

## Introduction to Spatial Data Science

Below are the R lab notes from Luc Anselin's [Introduction to Spatial Data Science](https://spatial.uchicago.edu/content/lectures-luc-anselin-uchicago) course at the University of Chicago. These labs mirror the [GeoDa notebooks](http://geodacenter.github.io/documentation.html), but use R rather than GeoDa.

* [**Spatial Data Handling**](https://spatialanalysis.github.io/lab_tutorials/1_R_Spatial_Data_Handling.html): Import, manipulate, and map abandoned vehicle data to make a choropleth map of abandoned vehicles per capita for Chicago community areas.
* [**Exploratory Data Analysis 1 - Univariate and Bivariate Analysis**](https://spatialanalysis.github.io/lab_tutorials/2_R_EDA_1.html): Explore NYC socioeconomic data by borough and perform exploratory spatial analysis involving univariate plots, smoothing methods, and linear fits.
* [**Exploratory Data Analysis 2 - Multivariate Exploration**](https://spatialanalysis.github.io/lab_tutorials/3_R_EDA_2.html): Continue to explore NYC socioeconomic data using spatial data analysis methods for three or more variables, including scatter plots, bubble plots, and parallel coordinate plots.
* [**Basic Mapping**](https://spatialanalysis.github.io/lab_tutorials/4_R_Mapping.html): Finish working with NYC socioeconomic data by creating and customizing a variety of maps, including choropleth maps, conditional maps, and cartograms.

![Choropleth Map of Abandoned Vehicle Per Capita in Chicago and Box Map of Rent in NYC](tutorials/choropleth-and-box-map.png)

## Basic R Tutorials

The following are notes that Luc Anselin has put together to introduce R to his undergraduate classes. They provide an overview of data manipulation and visualization methods, using geographic data as an example.

* [**Manipulating Data Frames**](html/dataframes-notebook.html): Read, write, summarize, and wrangle data with the `foreign` R package (for dbf files) and the `tidyverse`.
* [**Data Visualization (1)**](html/graphs1-notebook.html): Visualize data using the `ggplot2` package, creating scatterplots and fitting lines to NYC sub-borough data.
* [**Data Visualization (2)**](html/graphs2-notebook.html): Extend the visualizations of the previous tutorial, using `ggplot2` to customize scatterplots, create histograms, boxplots, and more. Learn about reshaping data into a tidy format using `tidyr`.
* [**Basic Mapping**](html/basic-mapping-notebook.html): Manipulate and map spatial data, creating custom choropleth maps with NYC borough data, using the `sf`, `tmap`, and `RColorBrewer` packages.
