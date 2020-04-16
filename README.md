#  Web Visualization Dashboard (Latitude)

## Description

Created a visualization dashboard website  with individual pages to analyze how weather changes as you get closer to the equator by pulling data from the OpenWeatherMap API to assemble a dataset on over 500 cities(Refer to Python API Repo). Factors looked included: temperature, cloudiness, wind speed, and humidity.

## Technologies
- Html
- CSS
- Bootstrap 
- Pandas

## The website must consist of 7 pages total, including:

### A landing page containing:


![](Web-Visualizations/Index.png)

An explanation of the project.
Links to each visualizations page.


### Four visualization pages, each with:

![](Web-Visualizations/TempandLat.png)

![](Web-Visualizations/HumLat.png)

![](Web-Visualizations/CloudLat.png)

![](Web-Visualizations/WindLat.png)

A descriptive title and heading tag.
The plot/visualization itself for the selected comparison.
A paragraph describing the plot and its significance.


### A "Comparisons" page that:


![](Web-Visualizations/Comparison.png)

Contains all of the visualizations on the same page.


### A "Data" page that:

![](Web-Visualizations/data.png)

Displays a responsive table containing the data used in the visualizations.

The data must come from exporting the .csv file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called to_html that allows you to generate a HTML table from a pandas dataframe. See the documentation here
