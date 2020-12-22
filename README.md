# Stock Market Trend Prediction by News Headlines and LSTM

Stock market investment is just another synonym for ‘risk and return’, the timely prediction of market direction remains one of the most challenging problems.
Yet, in the end, there are always people behind investments and lots of decision making is based on what they read in the news. In order to provide guidance
for individual investors.

This project proposes a deep learning-based stock index trend prediction model that considers the macro market sentiment and technical indicators. We develop an experimental framework for the classification problem which predicts next-day market direction. First, we incorporate sentiment context and technical indicators in the baseline `XGBoost` model. Second, we adopt `LSTM` and further revise it by introducing `ARIMA` prediction as an extra feature. A **novelty** of this work is about the joint application of **sentiment**, **technical indicators**, and **conventional time series techniques** in the **deep learning** framework. Investors would be equipped with the toolkit of both `fundamental analysis` as well as `technical metrics` to make informative and profitable investments.
