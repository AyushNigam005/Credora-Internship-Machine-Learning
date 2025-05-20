
# House Price Prediction - Credora Internship Task 01

This project implements a **Linear Regression** model to predict house prices using real-world data from the Kaggle competition:  
[House Prices - Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)

## Project Goals
- Handle missing values and preprocess housing data
- Scale numerical features
- Train a Linear Regression model using scikit-learn
- Evaluate performance using MAE, RMSE, and R²
- Visualize actual vs. predicted prices

## Features Used
- `GrLivArea`: Above ground living area (square feet)
- `BedroomAbvGr`: Number of bedrooms above ground
- `FullBath`: Number of full bathrooms

## Model Evaluation
After training and testing, model performance is measured using:
- **MAE (Mean Absolute Error)**
- **RMSE (Root Mean Squared Error)**
- **R² Score**

## Visualization
The model output includes a scatter plot comparing **Actual vs Predicted Prices**, giving a clear picture of how well the model is performing.

## 🚀 How to Run
1. Download the dataset from Kaggle and place `train.csv` in this folder.
2. Run the notebook in [Google Colab](https://colab.research.google.com/) or Jupyter.
3. Review the output report and plots.

## ✅ Tools & Libraries
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn


