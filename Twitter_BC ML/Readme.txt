Project name: Dogecoin (cryptocurrency) price prediction
Goal: Dogecoin price prediction based on Twitter sentiment analyses
Coders: Andrey Rogatin & Kirill Tiufanov
Summary: We took Dogecoin as one of the most influenced by public opinion crytpocurrency. We want run NLP model and analyse sentiments of the tweets to see how it influence the price. We take hourly period as a timeframe and analyse tweets with "bag of words" within each timeframe. We want our model to predict % change of the Dogecoin closing price in compare with opening price within hourly timeframe.

Datasets: 
1.Twitter tweets database for period of Jan'21 - Apr'22
3.5 M instances x 37 features
2.Dogecoin hourly price dataset for period of Jan'21 - Apr'22
16875 instances × 11 features

Plan:
Find data sets 05.12
  - with tweets
  - With Dogecoin indexes / stock data
  - Choose target value =(hor closure price)
Clean data/choose features  (Tweets) 06.12
  - Filter out tweets with less then N likes or retweets
  - Split by hour = hour label 
  - Subsplit by importance - tweets importance
  - Add target value  - growth or fall by 10%
Tweets processing + NLP 07.12
Tweets processed aggregate by hour 08.12
Clean/Process stock data 09.12
Merge to one data set 09.12
Data visualisation (heat map, correlations, hist) 12.12
Data transformation?
Lasso, Ridge. RFE etc 13.12
Regression model (ensamble) 13.12
Slides preparation 14.12
Party!


