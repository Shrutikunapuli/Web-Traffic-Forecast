# Web-Traffic-Forecast

As the internet's popularity has grown, it's become increasingly important to forecast web page traffic in order to manage web server loads. Predicting future traffic on diverse web pages is one of the most difficult challenges. Web traffic forecasting can be used to help with a range of web-related tasks. User behavior can be understood, future trends can be predicted based on past observations, a load balancing plan can be established in the cloud or on the server of web pages, user behavior can be understood, and products can be effectively marketed on pages with high visits based on user interests.


The data was approximately 145k wiki pages and days views were recorded. 1st of July 2015 to 31st of December 2016 550 days in total. The main objective of this project is to analyze and predict the future web traffic of the target website by using the past and current traffic on the target website. To better understand the nature of traffic and to predict the traffic accurately, we considered the following columns — article, locale, access, agents, and date from the data. 

Article name consists of the name of the article, locale holds the abbreviation of the country of access, while access specifies if the user is accessing from either desktop or a mobile application or both. Agents hold the data of the web crawlers like a spider. To make the training data easier to handle we apply the necessary steps of exploratory data analysis.
Data columns include- 1) Article name. 2) Access. 3) Agent. 4) Locale. 5) Date.

After performing the related exploratory data analysis, inference, and necessary feature extraction of columns. We forecast Wikipedia web traffic based on two months’ data and measure the prediction accuracy. Models used for forecasting web traffic for the hold out 60 days are ARIMA(Autoregressive integrated moving average) and AR(Auto regressor). For evaluation of the models built we use RMSE metrics, which tell the difference between predicted and actual values. 
