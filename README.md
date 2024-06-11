# PoliticsAndCovid
### Overview  
For our final project for CSCI 4022, Advanced Data Science, we were told we could do anything we wanted as long as we used a method we learned in the class. I decided to do my project on COVID-19 and how it might have been affected by politics. For my method I chose k-means and decided to see if I could cluster states to find something interesting.

This project required me to learn how to effectivly manage 3 different data sources, how to use geopandas and shape files, and how to effectivly interpret results from maps and graphs.  

This README will not include the conclusions I came to but rather an overview of how to use the code and background for the project. To see my analysis and conclusions see the project writeup.

### Project Code
The code and data for this project can be found in their respective folders. All major library imports are in the first cell of the Jupyter notebook to ensure it is easy to validate proper setup.  

For my project, I decided to use seeds to ensure the graphics I used in my presentation and write up can be recreated (all use the seed 2020). All the code needed to make the plots seen in the presentation and write up are provided in the Jupyter notebook.  

To use this code, simply organize the data in a new cell and use the desired plotting function. There are functions for simple linear regression, an elbow plot for k-means to check for the optimal number of clusters, one to plot the clustered states on a scatter plot, and finally two map plotting functions: one with Hawaii and Alaska, and one without.  