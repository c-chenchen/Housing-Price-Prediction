# California Housing Price Prediction

This project uses machine learning techniques to predict **median house prices in California** based on demographic and geographic features.

## Files in This Repository

House_prediction.ipynb # Main notebook containing data analysis and models
housing.csv # Dataset used for training and testing
README.md # Project documentation


## Project Overview
The goal of this project is to build and evaluate regression models that can accurately predict housing prices. The project includes data exploration, feature engineering, model training, and performance evaluation.

## Dataset
The dataset used is the California Housing dataset, which contains information such as:
- Median income
- House age
- Number of rooms and bedrooms
- Population
- Number of households
- Latitude and longitude
- Median house value (target variable)

## Methods Used
- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Feature engineering
- Machine learning regression models

## Models Implemented
- **Linear Regression**
- **Random Forest Regressor**

## Results
| Model | R² Score |
|------|----------|
| Linear Regression | 0.6675 |
| Random Forest | 0.8134 |

The Random Forest model achieved the best performance, demonstrating its ability to capture non-linear relationships in the data.

## How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/your-username/your-repo-name.git

```
2. Install required packages:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn

```
3. Open the notebook:
```bash
jupyter notebook House_prediction.ipynb

```
Author
```
Pirawit Kokiatwarakun


