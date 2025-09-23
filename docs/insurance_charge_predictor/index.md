# 💰 Insurance Charge Predictor

### Main Interface
![Main Interface](assets/icp0.png)

Welcome to the **AI-powered Insurance Charge Predictor**, an interactive Streamlit app that estimates your insurance charges based on personal information, lifestyle, and regional factors. The app also provides actionable recommendations and market insights.

---

## Features
- Predicts insurance charges using **PyCaret regression models**.
- Displays **personalized suggestions** to potentially reduce premiums.
- Interactive and responsive **Streamlit interface** with a modern design.
- Provides **market and demographic insights** based on sample data.
- Fallback **demo mode** if PyCaret or SHAP are unavailable.

## Screenshots

### Prediction & Recommendations
![Prediction Result](assets/icp1.png)

### Market Insights
![Market Insights](assets/icp2.png)

---

## How It Works

1. Enter your **personal information** (age, gender, height, weight, lifestyle, region) in the sidebar.  
2. The app calculates your **BMI** and predicts your **insurance charges**.  
3. Compare your estimate with **average charges** for your age group and region.  
4. Receive **personalized tips** to optimize your insurance cost.  
5. Explore **sample data** and insights from our dataset.

---

- **Try the App Live:** [Insurance charge predictor](https://insurancechargepredictorv1.streamlit.app)


## ⚙️ Tech Stack

- **Frontend & App:** [Streamlit](https://streamlit.io)  
- **Data Manipulation:** [Pandas](https://pandas.pydata.org/), [NumPy](https://numpy.org/)  
- **Machine Learning:** [PyCaret](https://pycaret.org/) (Regression)  
- **Explainable AI:** [SHAP](https://shap.readthedocs.io/)  
- **Visualization:** Matplotlib, Seaborn, Plotly  
- **Python Version:** 3.10+ recommended  

---
