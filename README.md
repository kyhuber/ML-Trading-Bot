# ML_Trading_Bot

Analysis of real estate data for San Francisco, including interactive visualizations and geospatial analysis.

First, the Proptech Analyzer computes the number of housing units and average sale price per square foot. The app groups this data by neighborhood and plots the trend over time. 

Next, the app considers gross rental data for each of the neighborhoods. In the resulting plot, the user can select a value from a dropdown and the plot will refresh to show neighborhood-specific data.

Finally, the app builds an interactive geospatial neighborhood map using latitude and longitude coordinates. This plot features color-coded dots within each neighborhood to provide an easy-to-follow visual interface.

The Proptech Analyzer creates value for users, namely investors, by calculating key metrics that are relevant in real estate. The plots and data visualizations simplify the complex CSV data for the investor. As demonstrated in the challenge, the app helps answer investment questions and tell a story using the data.

The app is written in such a manner that it can take in data from any city and is still just as useful.

---

## Technologies

The Proptech Analyzer is written in Python 3.10.1 using Jupyter Lab. It is compatible with Mac and PC OS.
The tool uses the Pandas libraries to collect, prepare, and analyze the data.
Data visualization plots are rendered using hvplot, along with GeoViews.

This app references raw data that is provided in a CSV file.

---

## Installation Guide

This app can be run in Gitbash or Terminal. The app and supporting files are located in the below Github repository:
https://github.com/kyhuber/Proptech-Analyzer

---

## Usage

To use the Proptech Analyzer, the user must have access to real estate data.

---

## Contributors

The ML Trading Bot was written by Kyle Huber in February 2022.

---

# ML_Trading_Bot
