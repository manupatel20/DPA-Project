# Analyzing Electric Vehicle (EV) Adoption Trends in Washington State 🚗🔋

This project explores the patterns, perceptions, and policy implications of electric vehicle (EV) adoption across Washington State. Using multiple structured datasets, we apply spatial, temporal, and statistical modeling to better understand EV growth trends, infrastructure alignment, and demographic influences.

## 📚 Project Overview

- **Goal:**  
  Identify geographic hotspots of EV adoption, forecast future registration trends, analyze electric vehicle characteristics, and evaluate charging infrastructure distribution.
  
- **Approach:**  
  - Exploratory Data Analysis (EDA)  
  - Multiple Linear Regression for electric range prediction  
  - ARIMA modeling for time-series forecasting of EV registrations  
  - K-means and DBSCAN clustering for charging station distribution  
  - Statistical significance testing (t-tests)

## 📈 Key Findings

- King County and other urban centers dominate EV adoption.
- Battery Electric Vehicles (BEVs) consistently outperform Plug-in Hybrid Electric Vehicles (PHEVs) in electric range.
- ARIMA forecasting predicts continued EV growth, though a plateau is expected in future years.
- Clustering reveals underserved rural areas for charging infrastructure expansion.
- Socioeconomic factors, particularly income and education, strongly influence EV adoption patterns.

## 🛠 Methodology

- **Data Preprocessing:**  
  Cleaning, feature engineering (e.g., Make_Model creation, vehicle age), and encoding categorical variables.

- **Model Training:**  
  - **Electric Range Prediction:** Multiple Linear Regression
  - **Charging Station Clustering:** K-means (balanced clusters) and DBSCAN (density-based clusters)
  - **Time-Series Forecasting:** ARIMA model with automatic parameter tuning

- **Model Evaluation Metrics:**  
  - RMSE and R-squared for regression models
  - Silhouette Score for clustering
  - AIC and residual analysis for ARIMA forecasting

- **Validation:**  
  Diagnostic plots, residual analysis, and cross-validation to confirm model reliability.

## 📊 Datasets

- [Electric Vehicle Population Data](https://data.wa.gov/Transportation/Electric-Vehicle-Population-Data/f6w7-q2d2)
- [Alternative Fueling Stations Data](https://data-usdot.opendata.arcgis.com/datasets/usdot::alternative-fueling-stations/about)
- [Electric Vehicle Title and Registration Activity](https://data.wa.gov/Transportation/Electric-Vehicle-Title-and-Registration-Activity/rpr4-cgyd/about_data)
- [Sentiment140 Dataset (tweets)](https://www.kaggle.com/datasets/kazanova/sentiment140)

> **Note:** Sentiment analysis was attempted but not pursued due to low relevance in tweet data quality.

## 🚀 Future Work

- Integrating real-time EV charging station usage data.
- Applying advanced ML models like XGBoost and Random Forest for adoption prediction.
- Enhancing spatial modeling using hierarchical clustering and spatial regression.
- Expanding analysis to benchmark Washington State against other ZEV-leading states.

## ✍️ Authors

- [Manushi Patel](mailto:mpatel188@hawk.iit.edu)
- [Tithi Patel](mailto:tpatel71@hawk.iit.edu)
- [Savan Jadav](mailto:sjadav1@hawk.iit.edu)


## 📖 Citation

If you use this project or any part of the analysis, please cite:

> [A record year for electric and plug-in hybrid vehicles in Washington](https://ecology.wa.gov/blog/april-2024/a-record-year-for-electric-vehicles-and-plug-in-hybrids-in-washington)

> [Global EV Outlook 2023 – Analysis - IEA](https://www.iea.org/reports/global-ev-outlook-2023)

> [EV, hybrid sales reached a record 20% of U.S. vehicle sales in 2024](https://www.cnbc.com/2025/01/16/electric-vehicle-ev-hybrid-sales-united-states-2024.html)

> [Electric Vehicle Sales Jump Higher in Q4, Pushing U.S. Sales to a Record 1.3 Million - Cox Automotive Inc. ](https://www.coxautoinc.com/market-insights/q4-2024-ev-sales/)

> [Results of Washington's EV Instant Rebate » Publications »](https://www.washingtonpolicy.org/publications/detail/results-of-washingtons-ev-instant-rebate)

> [Washington State EV Trends & Electric Car Research](https://www.recurrentauto.com/research/washington-electric-vehicles)

> [U.S. share of electric and hybrid vehicle sales increased in the second quarter of 2024 - U.S. Energy Information Administration (EIA)](https://www.eia.gov/todayinenergy/detail.php?id=62924)

> [Why Are U.S. EV Sales Flatlining?](https://www.forbes.com/sites/arielcohen/2024/07/26/why-are-us-ev-sales-flatlining/)

> [A comprehensive approach of evolving electric vehicles (EVs) to attribute “green self-generation” – a review](https://www.researchgate.net/publication/376546967_A_comprehensive_approach_of_evolving_electric_vehicles_EVs_to_attribute_green_self-generation_-_a_review)

> [Evolution of Electrical Vehicles, Battery State Estimation, and Future Research](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10720765)

> [The Evolution of Electric Vehicles: Technological Advancements and Market Dynamics](https://www.ijsr.net/archive/v13i5/SR24523184020.pdf)

> [Electric Vehicle Sentiment Analysis Using Large Language Models](https://www.mdpi.com/2813-2203/3/4/23)

> [Sentiment analysis of online reviews for electric vehicles using the SMAA-2 method and interval type-2 fuzzy sets - ScienceDirect](https://www.sciencedirect.com/science/article/abs/pii/S1568494623007639)
