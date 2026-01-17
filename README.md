# GREENWAY-INSIGHTS---FUEL-EFFICIENCY-PREDICTOR
# GREENWAY INSIGHTS – AI Fuel Efficiency Predictor

## 🚗 Project Overview

**Greenway Insights** is an intelligent fuel efficiency prediction solution for vehicles, developed as part of the IBM EdTech Youth Challenge. This project harnesses the power of machine learning to accurately estimate a car’s miles-per-gallon (MPG) by analyzing multiple accessible vehicle characteristics. It enables users, manufacturers, and policymakers to make informed decisions that benefit both the economy and the environment.[1]

***

## 🎯 Project Goals

- **Accurate Forecasts:** Predict a car’s MPG using technical parameters such as weight, horsepower, acceleration, etc.
- **Empower Users:** Deliver actionable insights to help maximize fuel savings.
- **Sustainability Focus:** Encourage eco-friendly vehicle design and policy-making by providing clear evidence-driven recommendations.[1]

***

## 📊 Key Features

- **Effortless Prediction:** Users input vehicle details; instant MPG predictions are delivered.
- **Visual Insights:** Actual vs. predicted MPG displayed via intuitive graphs for easy comparison and understanding.
- **Fuel Efficiency Classification:** Immediate notification of whether the entered vehicle is “fuel efficient” or “not fuel efficient” (>30 MPG threshold).[1]

***

## ⚙️ Technical Details

### Data Preparation

- **Dataset:** [UCI Auto MPG Dataset](https://www.kaggle.com/datasets/uciml/autompg-dataset)
- **Features:** cylinders, displacement, horsepower, weight, acceleration, model year, origin
- **Preprocessing:** Column cleaning, normalization, categorical encoding, and missing value handling

### Model Deployment

- **Algorithm:** Linear Regression (with code support for Random Forest Regressor)
- **Evaluation:** Measures used include Mean Absolute Error (MAE) and R² Score for precision and reliability
- **Visualization:** Interactive scatter plot illustrates model accuracy

***

## 🧑💻 Quick Start Guide

### Requirements

- Python 3.x
- Libraries: pandas, scikit-learn, matplotlib

### How to Use

1. Place `Auto_Data_Set_963_49.csv` in your project directory.
2. Update the file path in the script as needed.
3. Run the Python script:
   ```bash
   python greenway_insights.py
   ```
4. Enter the required vehicle details when prompted.
5. View the predicted MPG and classification result; the actual vs. predicted MPG graph will be displayed.

***

## ✅ User Experience Workflow

1. **Input Vehicle Specifications:**  
   - Cylinders, displacement, horsepower, weight, acceleration, year, origin.
2. **Instant Prediction:**  
   - The ML model calculates and reveals the MPG.
3. **Efficiency Classification:**  
   - Feedback on whether the car is fuel efficient.
4. **Visual Comparison:**  
   - Scatter plot of actual vs. predicted values for deeper analysis.[1]

***

## 🌟 Project Highlights & Future Roadmap

- **Simple & Accessible:** Easy-to-use interface makes predictions accessible to all.
- **Clear Visuals:** Graphical outputs aid understanding and decision-making.
- **Planned Enhancements:**  
  - Expand historical dataset for greater accuracy.
  - Broaden access through mobile/web applications.
  - Add advanced features (eco-driving tips, community sharing, gamification, real-time fuel price tracking).
  - Enhance security for user data and privacy.[1]

***