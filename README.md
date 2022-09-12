# ML_Trading_Bot

Creating a machine learning trading bot to inform decisions about returns based on different trading strategies.

First, the ML Trading Bot establishes a baseline performance from stock performance data contained within a csv file. Moving average values are calculated based on predefined inputs and creating trading signals. Next, the bot tunes the baseline trading algorithm using the support vector machine learning method. The app plots actual returns and strategy returns based on trading signals derived from the SVMLM.

Finally, the app reconsiders stock performance data using the LogisticRegression ML model.

The ML Trading Bot creates value for users, namely investors, by creating performance predictions. The bot can be tuned using any ML model and tested to view outcomes based on historical data.

The app is written in such a manner that it can take in data from any equity and is still just as useful.

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

Long SMA = 100, Short SMA = 4, Training Window = 3 months

These parameters establish a baseline for performance data. We can see that the strategy returns slightly exceed the actual returns using the SVC classifier model. The strategy returns exhibit similar volatility and trend lines.

![image](https://user-images.githubusercontent.com/69730757/162499783-737300bc-67bb-44ac-ad67-700d4c61c824.png)


### What impact resulted from increasing or decreasing the training window?

Long SMA = 100, Short SMA = 4, Training Window = 24 months

By increasing the training window, the strategy returns improves significantly.

![image](https://user-images.githubusercontent.com/69730757/162492502-5d2d0f59-af50-40a4-ad3a-422815843c6c.png)


### What impact resulted from increasing or decreasing either or both of the SMA windows?

Long SMA = 30, Short SMA = 1, Training Window = 3 months

By decreasing the long window to 30 and short to 1, we see good strategy returns but the trend line is more volatile.

![image](https://user-images.githubusercontent.com/69730757/162493558-93493025-e552-4cd4-a519-c83e3deb5568.png)


### Logistic Regression Model

Long SMA = 100, Short SMA = 4, Training Window = 3 months

The strategy returns and actual returns are more consistent using the logistic regression model, but they are not as favorable as the SVC model.

![image](https://user-images.githubusercontent.com/69730757/162497814-4cf7a5ba-db44-4256-836f-8014fd1e2c1b.png)


### Maximum Returns

Long SMA = 100, Short SMA = 1, Training Window = 24 months

By decreasing the short window, we see a sizable improvement of strategy returns in the SVC model. This combination of a longer long window, a shorter short window, and longer training window creates the best returns.

![image](https://user-images.githubusercontent.com/69730757/162492824-ff710fb2-7fda-4c02-8598-924328911b58.png)

---

## Contributors

The ML Trading Bot was written by Kyle Huber in April 2022.

---

# ML_Trading_Bot
