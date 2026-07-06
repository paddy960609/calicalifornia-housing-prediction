# California Housing Price Prediction

📓 Notebook: housingprice.ipynb

📊 Model Performance:
- RMSE: $45,116.54
- R²: 0.84

## Overview

This project develops a machine learning model to predict California housing prices using demographic, geographic, and housing characteristics from the California Housing Dataset.

The objective was to build an end-to-end machine learning pipeline, from exploratory data analysis and preprocessing to model training and evaluation, while demonstrating best practices in data analysis and predictive modeling.

---
## Why this project?

I completed this project to strengthen my machine learning skills by building a complete predictive modeling pipeline. Rather than focusing solely on model accuracy, I emphasized understanding the data, selecting appropriate evaluation metrics, and communicating results through clear visualizations and documentation.

## Dataset

- **Dataset:** California Housing Dataset
- **Source:** Scikit-learn
- **Records:** 20,640
- **Features:** 8 numerical predictors

Predictor variables include:

- Median Income
- House Age
- Average Rooms
- Average Bedrooms
- Population
- Average Occupancy
- Latitude
- Longitude

Target variable:

- Median House Value

---

## Project Workflow

### 1. Exploratory Data Analysis

- Examined data distributions
- Identified missing values
- Created correlation heatmap
- Visualized geographic housing prices across California
<img width="1018" height="682" alt="image" src="https://github.com/user-attachments/assets/1caeec72-467b-4871-bf80-c6674455544b" />

### 2. Data Preprocessing

- Removed missing values
- Selected predictor variables
- Split data into training and testing sets
- Prepared data for model training

### 3. Model Development

Implemented an **XGBoost Regressor** to model nonlinear relationships between housing characteristics and median house values.

### 4. Model Evaluation

Model performance was evaluated using:

- Root Mean Squared Error (RMSE)
- R² Score

---

## Results
<img width="562" height="455" alt="image" src="https://github.com/user-attachments/assets/0dc4369f-e451-41ca-833a-28d783acb396" />

| Metric | Value |
|---------|-------|
| RMSE | **$45,116.54** |
| R² Score | **0.84** |

The final model explains approximately **84% of the variation** in California housing prices while maintaining an average prediction error of approximately **$45,000**.

---

## Key Visualizations

The notebook includes:

- Feature distributions
- Correlation heatmap
- Geographic housing price visualization
- Feature importance analysis
- Actual vs. Predicted comparison
- Residual analysis
<img width="645" height="624" alt="image" src="https://github.com/user-attachments/assets/dc8ea8b1-72a6-43ec-8180-d0cbc7ee0b48" />

<img width="589" height="416" alt="image" src="https://github.com/user-attachments/assets/e92233e0-b774-4271-9b54-dfa9df7c52ad" />

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---

## Repository Structure

```
California-Housing-Prediction/
│
├── housingprice.ipynb
├── README.md
└── images/
```

---

## Future Improvements

Potential enhancements include:

- Hyperparameter optimization
- Cross-validation
- Comparison with Random Forest and LightGBM
- Additional feature engineering
- Model deployment as a web application

---

## Key Takeaways

This project demonstrates:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Machine learning model development
- Model evaluation and interpretation
- Data visualization
- End-to-end predictive analytics workflow
