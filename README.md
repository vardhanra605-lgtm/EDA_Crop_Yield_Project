# Crop Yield Analysis using EDA

Project Overview

This project focuses on Exploratory Data Analysis (EDA) of a crop dataset to understand how environmental and agricultural factors affect crop yield. The dataset contains 1000 records with features like temperature, rainfall, humidity, soil type, weather conditions, and crop type.

The goal is to extract meaningful insights and identify patterns that influence crop yield (tons/hectare).

---

Objectives

- Perform data cleaning and preprocessing
- Analyze numerical and categorical features
- Visualize relationships between variables
- Identify key factors affecting crop yield
- Build a basic prediction model

---

Dataset Description

Feature| Description
Temperature (°C)| Average temperature
Rainfall (mm)| Total rainfall
Humidity (%)| Humidity level
Soil Type| Type of soil (Sandy, Clay, Loamy, etc.)
Weather Condition| Weather type (Sunny, Rainy, Stormy)
Crop Type| Type of crop (Wheat, Corn, Barley, Soybeans)
Yield (tons/hectare)| Crop yield (target variable)

---

Technologies Used

- Python 
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

Exploratory Data Analysis (EDA)

Steps Performed

- Checked dataset structure and summary statistics
- Verified missing values
- Performed univariate analysis (histograms, countplots)
- Conducted bivariate analysis (scatter plots)
- Compared categorical features with yield (boxplots)
- Generated correlation heatmap
- Performed group-based analysis

---

Key Insights

- Crop yield varies significantly with rainfall and temperature
- Certain soil types provide better yield performance
- Weather conditions have a noticeable impact on crop productivity
- Some crops perform better under specific environmental conditions

---

Machine Learning Model

A simple Linear Regression model was implemented to predict crop yield.

Steps:

- Encoded categorical variables
- Split data into training and testing sets
- Trained Linear Regression model
- Evaluated model accuracy

---

How to Run the Project

1. Clone the repository

- git clone https://github.com/your-username/crop-yield-eda.git

2. Navigate to project folder

- cd crop-yield-eda

3. Install dependencies

- pip install pandas numpy matplotlib seaborn scikit-learn

4. Run the script

  - python eda_project.py

---

Future Improvements

- Use advanced ML models (Random Forest, XGBoost)
- Add feature engineering
- Deploy as a web application
- Integrate real-time agricultural data

---

Sample Visualizations

- Histogram of temperature, rainfall, humidity
- Scatter plots of yield vs environmental factors
- Boxplots for categorical variables
- Correlation heatmap

---

Conclusion

This project demonstrates how EDA helps uncover patterns and relationships in agricultural data. It provides insights that can assist farmers and researchers in improving crop yield.

---

Author

Vardhan R A
B.Tech IT (AI & ML)

---

Acknowledgement

Dataset used for educational and analytical purposes.
