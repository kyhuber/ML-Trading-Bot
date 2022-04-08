# ML_Trading_Bot

Analysis of real estate data for San Francisco, including interactive visualizations and geospatial analysis.

First, the Proptech Analyzer computes the number of housing units and average sale price per square foot. The app groups this data by neighborhood and plots the trend over time. 

Next, the app considers gross rental data for each of the neighborhoods. In the resulting plot, the user can select a value from a dropdown and the plot will refresh to show neighborhood-specific data.

Finally, the app builds an interactive geospatial neighborhood map using latitude and longitude coordinates. This plot features color-coded dots within each neighborhood to provide an easy-to-follow visual interface.

The Proptech Analyzer creates value for users, namely investors, by calculating key metrics that are relevant in real estate. The plots and data visualizations simplify the complex CSV data for the investor. As demonstrated in the challenge, the app helps answer investment questions and tell a story using the data.

The app is written in such a manner that it can take in data from any city and is still just as useful.

---

## Technologies

The ML Trading Bot is written in Python 3.10.1 using Jupyter Lab. It is compatible with Mac and PC OS.
The tool uses the Pandas libraries to collect, prepare, and analyze the data.
Data visualization plots are rendered using hvplot.
Machine Learning libraries come from SK Learn

This app references raw data that is provided in a CSV file.

---

## Installation Guide

This app can be run in Gitbash or Terminal. The app and supporting files are located in the below Github repository:
https://github.com/kyhuber/ML_Trading_Bot/

---

## Findings

![image](https://user-images.githubusercontent.com/69730757/162492392-36fd50ae-ec42-4715-99e1-e1641b4ef4ff.png)
Using 4 days for the short window and 100 days for the long, with a 3 month trading data set size, we can see that the strategy returns are much lower than actual.

What impact resulted from increasing or decreasing the training window?

![image](https://user-images.githubusercontent.com/69730757/162492502-5d2d0f59-af50-40a4-ad3a-422815843c6c.png)
By increasing the training window to 24 months, the strategy returns improves significantly.

What impact resulted from increasing or decreasing either or both of the SMA windows?

![image](https://user-images.githubusercontent.com/69730757/162492824-ff710fb2-7fda-4c02-8598-924328911b58.png)
By decreasing the short window to 1, we see a sizable improvement of strategy returns.

![image](https://user-images.githubusercontent.com/69730757/162493558-93493025-e552-4cd4-a519-c83e3deb5568.png)
By decreasing the long window to 30, we see good strategy returns but the trend line is more volatile.

---

## Contributors

The ML Trading Bot was written by Kyle Huber in April 2022.

---

# ML_Trading_Bot
