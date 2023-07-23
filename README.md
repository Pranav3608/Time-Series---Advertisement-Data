
# Time Series Analysis

This repository contains an analysis of the data provided in the file "dataset.csv." The analysis is performed using Python and various data analysis libraries.


## Data Overview

The dataset contains data of two marketing campaigns, Google Ads, and a listing site. The dataset was loaded and inspected to understand its structure and contents. It consists of several key columns, including:
Week: The date of the week.
Cost ($): The cost incurred.\
Payment ($): The payment received.\
Clicks: The number of clicks.\
Impressions: The number of impressions.\
Prospects: The number of prospects.\
Ad group: The ad group associated with the data.\
ROAS: The Return on Advertising Spend.\
CTR: The Click-Through Rate.\
Conversion_Rate: The conversion rate.
## Data preprocessing

The dataset was cleaned and prepared for analysis. Null values in certain columns were filled with 0. The Cost ($) and Payment ($) columns were converted to numeric data types. The Week and Payment Date columns were converted to datetime objects for time-based analysis.
## Key Metrics

Several key metrics were calculated from the dataset, including:

ROAS: The Return on Advertising Spend, calculated as the ratio of payment to cost.\
CTR: The Click-Through Rate, calculated as the percentage of clicks to impressions.\
Conversion Rate: The conversion rate, calculated as the percentage of prospects to clicks.




Please feel free to explore the Jupyter Notebook "Time_Series_Ads.ipynb" to view the complete analysis and code.
