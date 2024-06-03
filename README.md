# Time-Series-Analysis-of-a-Single-Stock


1. ARIMA (AutoRegressive Integrated Moving Average):
Definition: ARIMA, which stands for AutoRegressive Integrated Moving Average, is a popular time series forecasting model. It is a combination of three components: AutoRegressive (AR), Integrated (I), and Moving Average (MA). ARIMA models capture linear relationships between the observations and the historical data points.

Architecture:

AutoRegressive (AR) Component: It models the relationship between an observation and a fixed number of lagged observations (i.e., its own past values).
Integrated (I) Component: It represents the differencing of raw observations to make the time series stationary. This involves subtracting each observation from the previous observation to remove trends or seasonality.
Moving Average (MA) Component: It models the relationship between an observation and the residual errors from a moving average model applied to lagged observations.
Use Cases: ARIMA is widely used in finance, economics, and other fields for time series forecasting tasks, such as stock price prediction, demand forecasting, and sales forecasting.

Performance: ARIMA models can perform well for time series data with linear relationships and stationary behavior. However, they may struggle with highly non-linear and irregular data patterns.

2. SARIMA (Seasonal AutoRegressive Integrated Moving Average):
Definition: SARIMA, or Seasonal AutoRegressive Integrated Moving Average, extends the ARIMA model to account for seasonality in the data. It adds additional parameters to the ARIMA model to capture seasonal patterns.

Architecture:

Seasonal Component: SARIMA models include additional parameters for seasonal components, such as seasonal AR (SAR), seasonal difference (D), and seasonal MA (SMA). These parameters allow SARIMA models to capture seasonal variations in the data.
Non-Seasonal Component: SARIMA models also include the same AR, I, and MA components as ARIMA models.
Use Cases: SARIMA models are useful for time series data with clear seasonal patterns, such as monthly sales data, quarterly financial data, or daily temperature data.

Performance: SARIMA models can capture both the long-term trends and seasonal variations in the data. They are effective for forecasting tasks where seasonality plays a significant role.

3. Prophet:
Definition: Prophet is a forecasting tool developed by Facebook, designed to handle time series data with strong seasonal effects and multiple sources of uncertainty. It can capture daily, weekly, and yearly seasonality, as well as holidays and other special events.

Architecture:

Additive Time Series Components: Prophet models decompose time series data into additive components, including trend, seasonality, holiday effects, and error.
Piecewise Linear or Logistic Growth: Prophet uses piecewise linear or logistic functions to model non-linear growth trends in the data.
Automatic Changepoint Detection: Prophet automatically detects changepoints or abrupt changes in the time series data.
Holidays and Special Events: Prophet allows users to specify holidays and other special events that may impact the time series data.
Use Cases: Prophet is suitable for forecasting tasks with strong seasonal patterns, such as retail sales, website traffic, and demand forecasting.

Performance: Prophet is known for its flexibility, ease of use, and ability to handle complex time series data with multiple sources of uncertainty. It can provide accurate forecasts even with limited historical data and irregularly spaced observations.
