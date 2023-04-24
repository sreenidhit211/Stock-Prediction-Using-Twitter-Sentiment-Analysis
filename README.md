# Stock-Prediction-Using-Twitter-Sentiment-Analysis
Created using Kaggle Notebook

In recent years, Generative Adversarial Networks (GANs) have achieved good results in solving many complex problems (e.g., creating realistic images and videos, image-to-image and text-to-image conversion), but the effectiveness of using this type of network for stock price forecasting is still a matter of debate. This type of model was previously used mainly to generate new photos, videos, or texts, but not time series, especially as volatile as stock prices. The thing is that stock prices are usually a bit tougher to forecast due to market volatility and social influence on the trend of each stock.

Recently data scientists have started trying out GAN models for stock price prediction and some works show promising results. Moreover, news/social media analysis is becoming more and more used for this task, so why not try and combine those two approaches? :)

Therefore, in this project I created a model for forecasting Amazon, Google, Microsoft, Apple, and Meta stock prices which takes into account not only historical data and technical indicators, but also such external factors influencing the market as the mood of traders and brand reputation, which is represented in social media posts.

The algorithm is broken down into 5 sections:
1. Import packages
2. Get weekly sentiment for stock ticker
3. Get final dataset for training
4. Build GAN model
5. Train and test model
