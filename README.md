Cracking the Market Code with AI-Driven Stock Price Prediction

An AI-powered project that utilizes deep learning and time series analysis to predict stock prices with the help of LSTM neural networks, deployed through an interactive web app.

Table of Contents

Project Overview

Features

Tech Stack

System Requirements

Installation

Usage

Model Architecture

Results

Deployment

Future Scope

Team Members



---

Project Overview

Stock market prediction is notoriously difficult due to its non-linear, volatile nature. Traditional models often fail to capture the dynamic trends of market data. This project leverages AI techniques, particularly LSTM (Long Short-Term Memory) networks, to predict stock prices using historical time series data. The goal is to assist investors and traders in making data-driven decisions.


---

Features

Real-time stock prediction using LSTM

Web interface via Streamlit

Data preprocessing, EDA, and feature engineering

Model performance evaluation and visualization

Comparison with baseline models like Linear Regression and ARIMA



---

Tech Stack

Languages: Python 3.10+

Libraries: numpy, pandas, matplotlib, seaborn, scikit-learn, tensorflow, keras, streamlit

Platform: Streamlit Cloud



---

System Requirements

Minimum Hardware:

8 GB RAM


Recommended:

GPU-enabled system for faster training


Software:

Jupyter Notebook or Google Colab



---

Installation

1. Clone the repo:

git clone https://github.com/althaf-ak/cracking-the-market-code-with-ai.git
cd cracking-the-market-code-with-ai


2. Install dependencies:

pip install -r requirements.txt


3. Run the Streamlit app:

streamlit run app.py




---

Usage

Input a stock ticker and date range

View predicted vs actual price trends

Analyze stock behavior through visualizations



---

Model Architecture

Baseline models: Linear Regression, Random Forest Regressor

Advanced model: LSTM Neural Network (for temporal sequence learning)

Features: Moving averages, lag values, volatility measures

Evaluation Metrics: RMSE, MAE, R² Score



---

Results

LSTM demonstrated superior performance with lower RMSE and improved trend tracking

Visual comparison of actual vs predicted prices confirmed high model accuracy



---

Deployment

Live demo: https://cheerful-gingersnap-a26eca.netlify.app


---

Future Scope

Integrate news sentiment analysis for more context-aware predictions

Expand to multi-stock portfolio forecasting

Implement reinforcement learning for trading strategy optimization



---

Team Members

Althaf Ahmed – Project Lead, EDA & Visualization

Abrar Khan – Data Collection & Cleaning

Ahmed Ismail – Feature Engineering & Model Building

Almaajith – Model Evaluation & Report Presentation
