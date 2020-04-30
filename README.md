# [Time Series Forecasting using Python](https://courses.analyticsvidhya.com/courses/creating-time-series-forecast-using-python)
# Introduction
### What is time series forecasting?
Time series forecasting is considered a very important part of Machine learning, *often neglected* according to [jason's blog](https://machinelearningmastery.com/time-series-forecasting/). Its importance lies on the fact that many busness problems are fully dependant on time, for example sales of goods and/or services, or even stock markets.

Most common sectors that use it extensively in businesses could be Finance and Supply Chain Management (Demand forecasting). In this github, I am using one practical example through the course of the same name (embedded link on the title).
### What are the main components of the time series forecasting?
[business dictionary](http://www.businessdictionary.com/definition/time-series.html) describe the components in a simple yet effective way. Here there are
1. Seasonality: the seasonal variations that have a repetitive manner all the same every time in a specific period (this can be hour/day/week/month/quarter).
2. Trend: Variations of the data that move up and down from the mean in a predictable fashion, even by time trend can be increasing and you will see this here.
3. Cyclcial variations that are a subject of business or economic change, a product may reach its end life or economy has fallen and influenced demand
4. Random variations that do not fall under any of the mentioned categories.

You can [read more](https://www.toppr.com/guides/business-mathematics-and-statistics/time-series-analysis/components-of-time-series/) over the subject.
## Time series vs. regression
**N.B.: This part of the article is snatched from the course itself.**

Here you might think that as the target variable is numerical it can be predicted using regression techniques, but a time series problem is different from a regression problem in following ways:

- The main difference is that a time series is time dependent. So the basic assumption of a linear regression model that the observations are independent doesn’t hold in this case.
- Along with an increasing or decreasing trend, most Time Series have some form of seasonality trends,i.e. variations specific to a particular time frame.
So, predicting a time series using regression techniques is not a good approach.

Time series analysis comprises methods for analyzing time series data in order to extract meaningful statistics and other characteristics of the data. Time series forecasting is the use of a model to predict future values based on previously observed values.

# Problem statement
Unicorn Investors wants to make an investment in a new form of transportation - JetRail. JetRail uses Jet propulsion technology to run rails and move people at a high speed! The investment would only make sense, if they can get more than 1 Million monthly users with in next 18 months. In order to help Unicorn Ventures in their decision, you need to forecast the traffic on JetRail for the next 7 months.

# What else can be tried to improve your model further?
- You can try to make a weekly time series and make predictions for that series and then distribute those predictions into daily and then hourly predictions.
- Use combination of models(ensemble) to reduce the rmse. To read more about ensemble techniques you can refer these articles:
    
    I-https://www.analyticsvidhya.com/blog/2015/08/introduction-ensemble-learning/
    
    II- https://www.analyticsvidhya.com/blog/2015/09/questions-ensemble-modeling/
- To read further about the time series analysis you can refer these articles:
    
    I- https://www.analyticsvidhya.com/blog/2016/02/time-series-forecasting-codes-python/
    
    II- https://www.analyticsvidhya.com/blog/2018/02/time-series-forecasting-methods/
# Challenges faced
I faced some challenges during the outline of the course. Firstly the validation part using the modeling techniques, the root mean square error and the rmse laderboard. Coding difficutly in understanding the .fit() equation in the forecasting, but managed to find good references to further understand it. Finally the part involving the ACF And PACF, I provided a link to follow as a quick practice
# Important links
You can refer to the [practice problem](https://datahack.analyticsvidhya.com/contest/practice-problem-time-series-2/). Also you can go to the [discussion thread](https://discuss.analyticsvidhya.com/t/welcome-to-practice-problem-time-series-analysis/66154) for further inquiries and more information.
