# 📈 Netflix Subscriptions Forecasting

## 🎯 AIM
The aim of this project is to analyze the historical subscriber data for Netflix from 2013 to 2023 and build a forecasting model to predict future subscriber trends. By leveraging time series analysis and the ARIMA model, this project uncovers seasonal patterns and provides accurate forecasts to aid in strategic decision-making for Netflix's future growth.

---

## 📊 Data Explanation
The dataset contains historical subscriber numbers for Netflix over a period of 10 years, starting from 2013 to 2023. Each entry includes:

- **📅 Time Period**: A date representing when the subscriber count was recorded.
- **👥 Subscribers**: The total number of Netflix subscribers (in millions) at the corresponding time period.

### Example Data:
| Time Period   | Subscribers (in millions) |
|---------------|----------------------------|
| 01/04/2013    | 34.24M                     |
| 01/07/2013    | 35.64M                     |
| 01/10/2013    | 38.01M                     |
| 01/01/2014    | 41.43M                     |
| 01/04/2014    | 46.13M                     |

---

## 🛠️ Forecasting Model
For forecasting, we used the **ARIMA (AutoRegressive Integrated Moving Average)** model, which is a powerful and widely used time series analysis technique. The model parameters were carefully tuned to ensure high accuracy in forecasting Netflix subscriber trends.

---

## 📈 Results

The forecasting model successfully predicted the next 7 time points for Netflix's subscriber numbers. The predictions indicate a steady increase in subscriber growth over the forecasted period, with values nearing **278 million subscribers** by the end of the forecast.

### 📋 Predicted Values:
| Forecasted Index | Predicted Subscribers (in millions) |
|------------------|-------------------------------------|
| 42               | 243.32M                            |
| 43               | 248.25M                            |
| 44               | 253.18M                            |
| 45               | 258.11M                            |
| 46               | 263.03M                            |
| 47               | 267.96M                            |
| 48               | 272.88M                            |
| 49               | 277.81M                            |

---

## 📉 Graph Analysis
- **Blue Line**: Represents the historical Netflix subscriber data from 2013 to 2023.
- **Orange Line**: Represents the forecasted subscriber numbers for the next 7 time points.

The graph demonstrates a smooth continuation of the growth trend, suggesting that the ARIMA model successfully captures the underlying dynamics of Netflix subscriber growth.

---

## 🚀 Key Insights
- Netflix subscriber numbers show a consistent upward trend over time.
- The ARIMA model provides accurate predictions for future subscriber growth.
- These forecasts can be valuable for strategic planning and decision-making.

---
