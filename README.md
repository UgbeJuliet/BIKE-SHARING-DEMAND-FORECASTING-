# 🚲 Bike Sharing Demand Forecasting Using Machine Learning

## 📌 Project Overview

This project focuses on predicting bike rental demand using machine learning techniques. The objective is to analyze historical bike-sharing data, identify the factors that influence bike demand, and build predictive models that can accurately forecast the number of bike rentals.

The project follows a complete machine learning workflow, including data cleaning, exploratory data analysis (EDA), clustering, model building, evaluation, and model optimization.

---

## 🎯 Objectives

- Clean and preprocess the dataset.
- Perform Exploratory Data Analysis (EDA).
- Identify factors affecting bike rental demand.
- Apply K-Means clustering to discover hidden patterns.
- Build machine learning models to predict bike demand.
- Compare the performance of multiple models.
- Evaluate the models using regression metrics.
- Save the best-performing model for future use.

---

## 📂 Dataset

The project uses the **Bike Sharing Demand** dataset containing historical information about bike rentals and weather conditions.

### Features include:

- Datetime
- Season
- Holiday
- Working Day
- Weather Condition
- Temperature
- Feeling Temperature
- Humidity
- Wind Speed

### Target Variable

- **Count** (Total number of bike rentals)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

---

## 📊 Project Workflow

### Phase 1: Data Cleaning, Analysis and Visualization

- Loaded the dataset.
- Inspected data types and missing values.
- Cleaned and prepared the data.
- Performed Exploratory Data Analysis (EDA).
- Created visualizations to understand relationships between variables.
- Analyzed how weather and seasonal factors affect bike demand.

---

### Phase 2: Data Clustering and Model Building

- Standardized numerical features.
- Applied K-Means clustering.
- Prepared features for supervised learning.
- Split the dataset into training and testing sets.
- Built the following machine learning models:
  - Linear Regression
  - Random Forest Regression

---

### Phase 3: Model Evaluation and Optimization

- Evaluated models using:
  - Mean Absolute Error (MAE)
  - Root Mean Squared Error (RMSE)
  - R² Score
- Compared model performance.
- Visualized feature importance.
- Saved the best-performing model using Joblib.
- Documented conclusions and recommendations.

---

## 📈 Results

The Random Forest Regression model achieved the best performance by producing lower prediction errors and a higher R² Score compared to the Linear Regression model.

Key findings include:

- Temperature positively influences bike demand.
- High humidity and strong wind reduce bike usage.
- Weather conditions significantly affect rental patterns.
- Seasonal changes contribute to fluctuations in bike demand.

---

## 📁 Repository Structure

```
Bike-Sharing-Demand-Forecasting/
│
├── Bike_Sharing_Demand_Forecasting.ipynb
├── train.csv
├── bike_demand_model.pkl
├── README.md
└── images/
    ├── correlation_heatmap.png
    ├── demand_clusters.png
    ├── feature_importance.png
    └── model_comparison.png
```

---

## 📷 Visualizations

The project includes:

- Correlation Heatmap
- Bike Demand Distribution
- Cluster Visualization
- Feature Importance Chart
- Model Performance Comparison
- Actual vs Predicted Bike Demand

---

## 📌 Key Insights

- Weather conditions play a significant role in bike rental demand.
- Temperature is one of the strongest predictors.
- Random Forest outperformed Linear Regression in prediction accuracy.
- Machine learning can effectively forecast future bike demand.

---

## 🚀 Future Improvements

- Perform Hyperparameter Tuning using GridSearchCV.
- Deploy the model using Streamlit.
- Incorporate additional weather forecast data.
- Explore advanced algorithms such as XGBoost and LightGBM.
- Automate model retraining with new data.

---

## ▶️ How to Run

1. Clone the repository.

```bash
git clone https://github.com/yourusername/Bike-Sharing-Demand-Forecasting.git
```

2. Navigate to the project folder.

```bash
cd Bike-Sharing-Demand-Forecasting
```

3. Install the required libraries.

```bash
pip install pandas numpy matplotlib seaborn scikit-learn joblib
```

4. Open the Jupyter Notebook.

```bash
jupyter notebook
```

5. Run all cells to reproduce the analysis and model.

---

## 📚 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- K-Means Clustering
- Machine Learning
- Regression Analysis
- Model Evaluation
- Model Serialization
- Python Programming

