# Stock_Price_Prediction
This project aims to utilize news headlines for predicting the price of a stock.
News headlines will provide a score value that can be later used along with the closing prices of the stock in a model to predict the closing price of a particular stock.

The project can be broadly divided into three parts:
> Data Collection: This Data Collection can be divided into three subparts:
>> Web Scraping
>> Classification of Headlines to discard irrelevant categories
>> Providing labels corresponding to each date

> Predicting the movement of the stock
> Predicting the price of stock

News Headlines that will be used for dataset are from the archieves of '[The Economic Times]([url](https://economictimes.indiatimes.com/))' and '[The Times of India]([url](https://timesofindia.indiatimes.com/))'.
The file News_for_stock_Analysis.ipynb contains the code which was used for web scrapping and later, for fine-tuning a pre-trained model from Huggingface Hub that will be used in this project.
News_for_stock_Analysis.ipynb basically contains the accumulation of dataset and the models that will be used later.
