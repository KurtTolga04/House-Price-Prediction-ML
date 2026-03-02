# House Prices Prediction With Advanced Regression Techniques 🏡📈

## 📌 Project Overview
This project aims to predict housing prices using advanced machine learning regression techniques. By analyzing the complex and nonlinear relationships between property attributes and market values, this study compares the performance of different models to provide reliable price predictions. 

## 📊 Dataset
The dataset used in this project is the famous **Ames Housing Dataset** (`train.csv`). It contains various features regarding residential homes in Ames, Iowa, including:
* **LotArea:** Size of the lot in square feet.
* **YearBuilt:** Original construction date.
* **OverallQual:** Rates the overall material and finish of the house.
* **SalePrice:** The property's sale price in dollars (Target Variable).

## 🛠️ Technologies & Libraries Used
* **Language:** Python
* **Data Manipulation:** Pandas, NumPy
* **Data Visualization:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Random Forest, Linear Regression, PCA), XGBoost
* **Environment:** Jupyter Notebook

## 🚀 Methodology & Models
The study involves comprehensive Exploratory Data Analysis (EDA), feature engineering, and the application of Principal Component Analysis (PCA) for dimensionality reduction. 

The core of the project compares the predictive performance of the following models:
1. **Random Forest Regressor**
2. **XGBoost Regressor**
3. **Linear Regression** (as a baseline)

Models are evaluated based on metrics such as **RMSE** (Root Mean Squared Error) and **R² Score**.
According to these results, XGBoost is the most succesfull model among others in this project. You can check project report.

## 📁 Repository Structure
```text
├── plots/                                                       # Directory for EDA and result plots
│   ├── price_distribution.png                                    # Example plot (Add your own)
│   └── model_comparison.png                                      # Example plot (Add your own)
├── HousePricePrediction.ipynb                                    # Main source code and analysis
├── train.csv                                                     # Training dataset
├── House Prices Prediction With Advanced Regression Techniques.pdf # Detailed academic project report
└── README.md                                                     # Project documentation

Tolga Kurt
