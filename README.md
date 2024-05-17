# Stocks Time Series Forecasting
Project on Stock Time Series Forecasting using multiple Deep Learning Models. Developed by Ian Wong Han Li, Simon See Yongsheng, Bryan Lee Jie Long, Zandra Tay, Chua Ler Han and Tan Si Xuan

## Introduction:
Welcome to the repository page of Stock Time Series Forecasting, developed for the NUS course: Mining Web Data for Business Insights 

## Dataset
The forecasting project utilises scraped online stock data for the datasets. Data were extracted from
- Stocks information: [yfinance package](https://pypi.org/project/yfinance/)
- Economic information: [fredapi package](https://pypi.org/project/fredapi/)
- Stock sentiment data: [polygon.ai](https://polygon.io/)
- Stock company's Quarterly and Annual report information: [SEC EDGAR API](https://www.sec.gov/edgar/sec-api-documentation) 

## Machine Learning Models
We utilised different machine learning models to investigate the single best model in stock price forecasting. Models tested includes:
- XGBoost
- Random Forest Regressor
- LSTM
- GRU
- Google Temporal Fusion Transformer (Google TFT)

## Evaluation:
> ![Google TFT test prediction for Google TFT for Jan-June 2020](./img/Google%20TFT%20test%20prediction%20Jan-June%202020.png "")
<p align="center">
    Plot of predicted stock price (red) against actual stock price for Jan-June 2020 by Google TFT model, for one stock price day later 
</p>

Overall, Google TFT emerged as the most accurate model for stock price prediction, yielding the lowerst average RMSE score of 8.92 for prediction during the COVID-19 pandemic from January to June 2020. 

Our team recommends futureu research into stock price prediction to investigate different stock-related data with the Google TFT deep learning model. 

For a detailed analysis, please refer to the [Final Report](./Final_Report.pdf "").


## How to use:
- Install visual studio code on computer and install relevant git extensions if needed
- On visual studio code's terminal, enter: ```git clone https://github.com/ianwonghanli/Stocks_Time_Series_Forecasting.git```
- Run all code blocks in [Source code file](./Source_code.ipynb "")

Detailed documentation of each file in repository can be found in [Instructions for use](./Instructions_for_use.pdf ""). 

## Further Information
For further information or usage of the project, please contact:
- Ian Wong at ian.wong.han.li@gmail.com or
- Simon See Yongsheng at simonseeyongsheng@gmail.com or
- Bryan Lee Jie Long at bryanjielong@gmail.com or
- Zandra Tay at zandratxy@gmail.com or
- Chua Ler Han at chualerhan@gmail.com or
- Tan Si Xuan at tansixuantsx@gmail.com
