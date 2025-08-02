## AICTE Internship Cycle 2 – July 2025  
### Project: Electric Vehicle (EV) Charging Demand Prediction

---

### Project Description

This project aims to develop a machine learning model that forecasts electric vehicle (EV) charging demand using historical vehicle registration data and regional characteristics

With the rapid growth of EV adoption, accurate demand forecasting is essential for urban planners and policymakers to ensure proper infrastructure planning—especially for the installation of charging stations. The project includes data preprocessing, exploratory data analysis, and the application of regression techniques to predict future EV trends across counties

---

### Problem Statement

Using an electric vehicle dataset (which includes information on EV populations, vehicle types, and possibly historical charging usage), this project builds a model that forecasts future EV adoption. For example, predicting the number of electric vehicles in upcoming years based on past trends

---

### Goal

To build a regression model that forecasts future EV adoption demand based on historical trends in EV growth, vehicle types, and regional data

---

### Objectives

- Analyze EV registration trends across time and regions  
- Perform data cleaning and exploratory data analysis  
- Build a regression model to forecast future EV adoption  
- Support sustainable infrastructure planning using predictive insights  

---

### Tools and Libraries Used

- **Language**: Python (Jupyter Notebook)  
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  

---

### Dataset Description

This dataset includes monthly vehicle registration counts collected by the Washington State Department of Licensing (DOL), covering multiple counties from 2017-01-31 to 2024-02-29

**Key Features:**

- **Date**: End-of-month registration snapshot  
- **County**: County of residence of the vehicle owner (Washington)  
- **State**: U.S. state associated with the record  
- **Vehicle Primary Use**: Passenger (83%) or Truck (17%)  
- **Battery Electric Vehicles (BEVs)**: Fully battery-powered vehicles  
- **Plug-In Hybrid Electric Vehicles (PHEVs)**: Partially battery-powered vehicles  
- **EV Total**: Sum of BEVs and PHEVs  
- **Non-EV Total**: Count of all non-electric vehicles  
- **Total Vehicles**: All registered powered vehicles  
- **Percent EV**: Percentage of EVs in the total vehicle population  

---

### Dataset Source

[Kaggle – Electric Vehicle Population Size 2024](https://www.kaggle.com/datasets/sahirmaharajj/electric-vehicle-population-size-2024/data)

---

### Outcome

The final model helps identify areas with rising EV demand, enabling data-driven decisions for infrastructure investments and contributing to sustainable and smart mobility solutions

---

## Weekly Progress

### Week 1 – Data Exploration and Initial Setup

- Loaded and explored the raw EV registration dataset (`Electric_Vehicle_Population_By_County.csv`)
- Identified top counties with the highest EV adoption
- Created the initial notebook (`EV_Adoption_Forecasting.ipynb`)
- Conducted exploratory data analysis (EDA) using visualizations and statistics
- Plotted cumulative EV adoption across counties
- Exported a Random Forest regression tree visualization (`RF_Tree.png`) to understand model behavior
- Added basic markdown documentation and outlined the project direction

---

### Week 2 – Forecasting & Modeling Progress

- Cleaned and preprocessed the dataset (`preprocessed_ev_data.csv`)
- Updated and refined the main notebook (`EV_Adoption_Forecasting.ipynb`) with structured markdowns, improved comments, and forecasting workflow
- Built and evaluated regression models for short-term EV adoption prediction
- Visualized both historical trends and future projections for top counties
- Saved the trained model as a pickle file (`ev_adoption_model.pkl`) for future use or deployment

---

### Final Submission – Streamlit Dashboard (Local Deployment)

- Built an interactive dashboard in `app.py` using Streamlit
- Integrated trained model (`forecasting_ev_model.pkl`) for EV adoption forecasting
- Enabled county-wise trend visualization with 3-year projections
- Added thematic image (`ev-car-factory.jpg`) for better UI
- Successfully tested the app locally via the VS Code terminal
- Listed dependencies in `requirements.txt` for reproducibility

---

## Acknowledgment

This project was completed as part of the **AICTE Internship Cycle 2 by S4F**, focused on electric vehicle analytics and demand forecasting.






