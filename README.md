# Time-Series---Advertisement-Data
Omnify Data Analysis
This repository contains an analysis of the data provided in the file "dataset.csv." The analysis is performed using Python and various data analysis libraries.

Data Overview
The dataset contains data of two marketing campaigns, Google Ads, and a listing site. The dataset was loaded and inspected to understand its structure and contents. It consists of several key columns, including:

Week: The date of the week.
Cost ($): The cost incurred.
Payment ($): The payment received.
Clicks: The number of clicks.
Impressions: The number of impressions.
Prospects: The number of prospects.
Ad group: The ad group associated with the data.
ROAS: The Return on Advertising Spend.
CTR: The Click-Through Rate.
Conversion_Rate: The conversion rate.
Data Preprocessing
The dataset was cleaned and prepared for analysis. Null values in certain columns were filled with 0. The Cost ($) and Payment ($) columns were converted to numeric data types. The Week and Payment Date columns were converted to datetime objects for time-based analysis.

Key Metrics
Several key metrics were calculated from the dataset, including:

ROAS: The Return on Advertising Spend, calculated as the ratio of payment to cost.
CTR: The Click-Through Rate, calculated as the percentage of clicks to impressions.
Conversion Rate: The conversion rate, calculated as the percentage of prospects to clicks.
Weekly and Monthly Reports
The data was grouped by week and month to create weekly and monthly reports. These reports provide insights into the average Cost ($), ROAS, CTR, and Conversion_Rate over time.

Most Profitable Channel and Category/Keyword
The most profitable channel and category/keyword were identified based on the highest average ROAS values. The most profitable channel is represented by the variable most_profitable_channel, and the most profitable category/keyword is represented by the variable most_profitable_category.

Time Series Analysis
Time series analysis was performed for ROAS, CTR, and Conversion Rate. Plots were created to visualize their trends over time.

Seasonality Analysis
The seasonal decomposition of ROAS was performed using moving averages and visualized in a plot to identify any seasonal patterns.

Trend Analysis
A 5-day rolling average was calculated for CTR and visualized along with the original CTR values to observe the overall trend.

Anomaly Detection
Anomaly detection was performed based on the Conversion Rate using Z-scores. Data points with Z-scores greater than 3 were considered anomalies and visualized in a scatter plot.

Correlation Analysis
A correlation matrix was created to understand the relationships between ROAS, CTR, and Conversion Rate. The matrix was visualized as a heatmap.

Insights from Keyword Type
Metrics were plotted for each keyword type (Keyword type) to gain insights into their performance in terms of ROAS, CTR, and Conversion Rate.

Most Searched Keyword
The most searched keyword and the number of times it was searched were identified from the data.

Visualizing the Search Keywords
The top 10 most searched keywords were visualized in a pie chart.

Impressions by Ad Group
The ad groups with the highest number of impressions were identified and visualized in a bar chart.

Campaigns with Top Prospects and Sales
Campaigns were analyzed based on the number of prospects and sales generated from them. The data is shown in the table format.

Please feel free to explore the Jupyter Notebook "Time Series Ads.ipynb" to view the complete analysis and code.
