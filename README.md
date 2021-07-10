# StockPricePredictionBasedOnHeadlines
* Create a model (based on NLP) to predict the stock price using News Headline
* This model uses headlines of top 25 articles based on that stock price fluctuate.
* Used sentiment analysis on headlines using NLP and the model created  will predict the stock will increase or decrease
## Data Description
* Used Kaggle data set.
* The data frame 2000 to 2008 was scrapped from yahoo finance.
* 25 columns of top news headlines for each day in the data frame and Date are independent features.
* Label is the dependent feature.
  * Class 1 – The stock price increased.
  * Class 0 – The stock price stayed the same or decreased.

https://colab.research.google.com/gist/Anjana85/956304be0a401cb8a1d70399426e79e5/stockpricepredictionbasedonheadlines.ipynb


#######  Here is [my code ] [https://colab.research.google.com/drive/1hC-W-1izSZDCf7r1ZD08FCuK472lZsZD?usp=sharing]
## Conclusion 
  * If you have to predict stock for tomorrow, take the top 25 news headlines apply all the transformation methods, and finally give it to your model, your model will predict the output as 0 or 1. If it is 0 means stock price is decreasing or stayed same, '1' means stock price is increasing.
