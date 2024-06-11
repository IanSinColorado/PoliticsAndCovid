# PoliticsAndCovid
## Overview  
For the final project for CSCI 4022, Advanced Data Science, we were told we could do anything we wanted as long as we used a method we learned in class. I decided to do my project on COVID-19 and politics, specifically how politics affected the COVID-19 cases of states in the United States. For my method, I chose k-means to see if I could cluster states to find something interesting.  

This project required me to learn how to manage 3 different data sources effectively, use geopandas and shape files, and interpret cluster results from maps and graphs.  

This README will not include the conclusions I came to but rather an overview of how to use the code and background for the project. To see my analysis and conclusions, please see the project write-up.  

## Project Code
The code and data for this project can be found in their respective folders. All major library imports are in the first cell of the Jupyter Notebook to ensure it is easy to validate the proper setup for imports.  

For my project, I decided to use seeds to ensure the graphics I used in my presentation and write up can be recreated (all use the seed 2020). All the code needed to make the plots seen in the presentation and write-up are provided in the Jupyter Notebook.  

To use this code, create a new cell, organize the data in a new cell, and finally use the desired plotting function. There are functions for simple linear regression, an elbow plot for k-means to check for the optimal number of clusters, one to plot the clustered states on a scatter plot, and finally two map plotting functions: one with Hawaii and Alaska, and one without. The colors might not correlate between functions and clusters because the clusters are randomized with every run of the k-means clustering algorithm.
