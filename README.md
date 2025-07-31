# 📈 EV Adoption Forecasting-EV Vehicle/Charging Demand Prediction
<img width="1338" height="158" alt="image" src="https://github.com/user-attachments/assets/e5c22aae-3ca1-4b0a-8f75-f4b1b57d8228" />


<h1 align="center">Hi 👋, I'm Raghav</h1>
<h3 align="center">Forecasting Electric Vehicle Growth in Washington State using Time Series Analysis</h3>

<p align="center">
  <img src="https://img.shields.io/badge/status-in--progress-yellow?style=flat-square&logo=github" alt="Project Status"/>
  <img src="https://img.shields.io/badge/Made%20with-Python-blue?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/github/stars/raghavj12345/EV-Adoption-Forecasting?style=social" alt="GitHub Stars"/>
</p>

---

## 📌 About the Project

As electric vehicle (EV) adoption surges, urban planners need to anticipate infrastructure needs—especially charging stations. Inadequate planning can lead to bottlenecks, impacting user satisfaction and hindering sustainability goals.

This project aims to address this challenge by building a **regression model that forecasts future EV adoption** based on historical trends in vehicle growth, types of vehicles, and regional data from Washington State.

---

## 🎯 Key Objectives

- 🔍 **Analyze** historical trends in EV registration data from 2017 to 2024.
- 🧹 **Clean and preprocess** the dataset for time series analysis.
- 🤖 **Build and train** a robust regression model to forecast the number of electric vehicles in upcoming years.
- 📊 **Visualize** the forecasted adoption rates to provide clear, actionable insights for infrastructure planning.
- 🛠️ **Evaluate** the model's performance to ensure accurate and reliable predictions.

---

## 📊 Dataset Overview

This project uses a dataset from the **Washington State Department of Licensing (DOL)**, which shows the number of vehicles registered each month.

- **Date Range:** January 2017 - February 2024
- **Key Features:**
  - `County`: Geographic region of the vehicle's owner.
  - `Vehicle Primary Use`: Passenger (83%) or Truck (17%).
  - `Battery Electric Vehicles (BEVs)`: Count of fully electric vehicles.
  - `Plug-In Hybrid Electric Vehicles (PHEVs)`: Count of plug-in hybrids.
  - `EV Total`: The sum of BEVs and PHEVs.

---

## 🛠️ Tools & Technologies

<p align="left">
  <a href="https://www.python.org/" target="_blank"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/></a>
  <a href="https://pandas.pydata.org/" target="_blank"><img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/></a>
  <a href="https://numpy.org/" target="_blank"><img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white"/></a>
  <a href="https://seaborn.pydata.org/" target="_blank"><img src="https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge&logo=seaborn&logoColor=white"/></a>
  <a href="https://matplotlib.org/" target="_blank"><img src="https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=matplotlib&logoColor=white"/></a>
  <a href="https://scikit-learn.org/" target="_blank"><img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/></a>
</p>

---

## 🚀 Future Roadmap

- ✅ **Exploratory Data Analysis (EDA):** Complete a deep dive into the historical data to identify seasonality and trends.
- 🧠 **Feature Engineering:** Create time-based features (e.g., month, year, quarter) to improve model accuracy.
- 🤖 **Model Development:** Train and evaluate multiple time series or regression models (e.g., ARIMA, Prophet, or Linear Regression).
- 📈 **Visualize Forecasts:** Create clear plots showing the predicted EV growth against the historical data.
- ☁️ **Deployment (Optional):** Deploy the final model as an interactive Streamlit dashboard or a simple API.

---

## 🤝 Connect with me

<p align="left">
  <a href="https://github.com/raghavj12345" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-black?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://www.linkedin.com/in/raghav-joshi-687a02373" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
</p>

---

⭐️ *If you find this project interesting, please consider giving it a star to support my work.

# 📈 EV Adoption Forecasting-EV Vehicle/Charging Demand Prediction
<img width="1338" height="158" alt="image" src="https://github.com/user-attachments/assets/e5c22aae-3ca1-4b0a-8f75-f4b1b57d8228" />

<h1 align="center">Hi 👋, I'm Raghav</h1>
<h3 align="center">Forecasting Electric Vehicle Growth in Washington State using Time Series Analysis</h3>

<p align="center">
  <a href="https://evchargingprediction-tkfusxpyhmxkvkivseemmf.streamlit.app/"><img src="https://img.shields.io/badge/status-live demo-brightgreen?style=flat-square" alt="Project Status"/></a>
  <img src="https://img.shields.io/badge/Made%20with-Python-blue?style=flat-square&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/github/stars/raghavj12345/EV-Adoption-Forecasting?style=social" alt="GitHub Stars"/>
</p>

---

## 🚀 Live Demo

### [➡️ Click here to try the interactive EV Forecaster App!](https://evchargingprediction-tkfusxpyhmxkvkivseemmf.streamlit.app/)

Here's a quick look at the application in action:

<p align="center">
  <img src="https://github.com/RAgHavj12345/EV_Charging_Prediction/assets/136015560/5948348a-a43b-486a-ad85-9b2f664c9d5d" width="800" alt="App Screenshot"/>
</p>


---

## 📌 Project Overview

As electric vehicle (EV) adoption surges, urban planners need to anticipate infrastructure needs—especially charging stations. This project addresses this challenge by building and deploying a **time-series forecasting model** that predicts future EV adoption based on historical registration data from Washington State. The goal is to provide clear, actionable insights for infrastructure planning.

---

## ✨ Key Features

- 🔍 **In-Depth Analysis:** Analyzes historical trends in EV registration data from 2017 to 2024.
- 🤖 **Robust Forecasting Model:** Uses a Gradient Boosting model with lag features and rolling statistics to predict monthly EV registrations.
- 📊 **Interactive Dashboard:** A live web app built with Streamlit that allows users to:
    - Select a county to see a 3-year EV adoption forecast.
    - Compare the growth trends of up to 3 different counties side-by-side.
- 📈 **Clear Visualizations:** Generates dynamic plots showing the historical vs. forecasted cumulative EV counts.

---

## 🛠️ Tools & Technologies

<p align="left">
  <a href="https://www.python.org/" target="_blank"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/></a>
  <a href="https://pandas.pydata.org/" target="_blank"><img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/></a>
  <a href="https://scikit-learn.org/" target="_blank"><img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white"/></a>
  <a href="https://streamlit.io/" target="_blank"><img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white"/></a>
  <a href="https://matplotlib.org/" target="_blank"><img src="https://img.shields.io/badge/Matplotlib-3776AB?style=for-the-badge&logo=matplotlib&logoColor=white"/></a>
</p>

---

## 🤝 Connect & Support

If you find this project interesting or useful, please consider giving it a ⭐️! You can also connect with me here:

<p align="left">
  <a href="https://github.com/raghavj12345" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-black?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://www.linkedin.com/in/raghav-joshi-687a02373" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-blue?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
</p>
