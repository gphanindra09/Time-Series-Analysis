# Time-Series-Analysis
project title:Analysis and prediction of microsoft_stock.csv file which contains stocks and credits of IT firms.Prediction the value of stocks in future by 3 category in a {{open}},'high low'

Time Series Analysis
A Time Series is a set of observations that are collected after regular intervals of time. If plotted, the Time series would always have one of its axes as time. Time Series Analysis in Python considers data collected over time might have some structure; hence it analyses Time Series data to extract its valuable characteristics. image.png
Name:G.Phanindra
Roll No:20X01A6702
Branch:lV year cse(data science)
College:Narsimha Reddy Engineering College
project title:Analysis and prediction of microsoft_stock.csv file which contains stocks and credits of IT firms.Prediction the value of stocks in future by 3 category in a {{open}},'high low'
problem statement: This comprehensive dataset provides a detailed analysis of Microsoft Corporation's stock performance from 1986 to 2023. It encompasses various important parameters, including stock price, low price, *high * price, and trading volume, to provide a comprehensive overview of the company's market behavior throughout the years.
The dataset begins in 1986, marking the early years of Microsoft's presence in the stock market. As one of the pioneering companies in the technology industry, Microsoft's stock performance has been closely followed by investors, analysts, and enthusiasts alike. The dataset captures the fluctuations and trends in the stock market, reflecting the company's journey from its inception to its position as a global tech giant.
The stock price data offers a glimpse into the market valuation of Microsoft shares over time. By observing the daily closing prices, one can track the trajectory of the stock and identify key milestones in Microsoft's history. The dataset also includes the lowest and highest prices reached during each trading day, offering insight into the price range within which the stock fluctuated.
Trading volume data provides an additional dimension for understanding Microsoft's stock market activity. It highlights the level of investor interest and participation in buying and selling Microsoft shares during each trading day. Tracking trading volume can help identify periods of increased market activity or significant news events that influenced investor sentiment.
The dataset covers a span of several decades, enabling users to analyze long-term trends, market cycles, and historical patterns that have shaped Microsoft's stock performance. It can be used by researchers, investors, and analysts to conduct quantitative and qualitative studies, perform technical analyses, and gain insights into the dynamics of the technology industry and the broader market.
3Please note that this dataset serves as a valuable historical resource and should be utilized alongside other relevant financial information and analysis to make informed decisions. The dataset captures Microsoft's stock performance up until 2023, ensuring that users have access to the latest available information.
Description: The Dataset provides the history of daily price of microsoft stocks depending USD
We'll be using the pmdarima library for automatic ARIMA model selection, as it simplifies the process of finding the optimal parameters for the ARIMA model.
Loading and Exploring Data:
# Load your time series data into a pandas DataFrame
Visualizing Time Series:
# Plot the time series data
![image](https://github.com/phani12-gp/Time-Series-Analysis/assets/123863815/4abae7bb-ecbd-40ae-929b-c37e4cd650a0)
![image](https://github.com/phani12-gp/Time-Series-Analysis/assets/123863815/0f9da9bf-b3dd-410d-b497-36b3e4299faf)


Decomposing Time Series into Components:
Trend:
The Trend shows the variation of data with time or the frequency of data. Using a Trend, you can see how your data increases or decreases over time. The data can increase, decrease, or remain stable. Over time, population, stock market fluctuations, and production in a company are all examples of trends.
Seasonality:
Seasonality is used to find the variations which occur at regular intervals of time. Examples are festivals, conventions, seasons, etc. These variations usually happen around the same time period and affect the data in specific ways which you can predict.
Irregularity:
Fluctuations in the time series data do not correspond to the trend or seasonality. These variations in your time series are purely random and usually caused by unforeseeable circumstances, such as a sudden decrease in population because of a natural calamity.
Cyclic:
Oscillations in time series which last for more than a year are called cyclic. They may or may not be periodic.
Stationary:
A time series that has the same statistical properties over time is stationary. The properties remain the same anywhere in the series. Your data needs to be stationary to perform time-series analysis on it. A stationary series has a constant mean, variance, and covariance.
Decomposition in Time series analysis:
The decomposition of time series is a statistical task that deconstructs a time series into several components, each representing one of the underlying categories of patterns.
The syntax of decomposition is:

decomposition = seasonal_decompose(data[" PARTICULAR COLUMN NAME"], model='additive', period= 12)

seasonal for types of Time series, model is alway be default for additive and period ios 12 months of in one year.

plt.subplot(nnn)

1.The first digit (n) represents the number of rows in the grid.
2.The second digit (n) represents the number of columns in the grid.
3.The third and last digit (n) represents the index of the current subplot within the grid.

![image](https://github.com/phani12-gp/Time-Series-Analysis/assets/123863815/9d760870-c6aa-4e93-9837-fe2180bea71f)

![image](https://github.com/phani12-gp/Time-Series-Analysis/assets/123863815/a631b9ec-bfa4-4866-bf44-ca5a8ffca3ed)

Import scipy

![image](https://github.com/phani12-gp/Time-Series-Analysis/assets/123863815/35b32ed4-559e-4a27-b3e0-738cb1d332a8)

![image](https://github.com/phani12-gp/Time-Series-Analysis/assets/123863815/5075f0fc-64b2-4d40-b046-365ecef993dd)
![image](https://github.com/phani12-gp/Time-Series-Analysis/assets/123863815/305cae4e-ccaf-4c71-8631-6a64312e653c)

CONCLUSION:According to the time series of data for this particular dataset we found that,open,high,low,close,are the columns in which the trades in increasing manner but in the year 2020 and 2021 The stocks are goes in deceasing manner
According to the volume charts of this particualr dataset for the year 2016 to 2017 gives a littl bit of of more profit to investment in the stocks after 2017 and upcoming year the stocks will be fluctuated






