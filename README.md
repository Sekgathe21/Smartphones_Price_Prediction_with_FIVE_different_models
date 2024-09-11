# Smartphone Price Prediction Using Multiple Machine Learning Models

## Author
**Sekgathe Karabo Matlala**  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sekgathe-karabo-matlala-13996b217/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)](https://github.com/Sekgathe21)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=flat&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UC2x4wrj2gQRLukNg7-Ces1Q)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat&logo=codepen&logoColor=white)](https://www.datascienceportfol.io/SekgatheKM22)

---

## 📝 Project Overview

### 🎯 Objective
This project focuses on predicting smartphone prices using various machine learning models. The dataset comprises smartphone specifications, including RAM, storage, brand, model, and price. The goal is to create models that accurately predict smartphone prices based on these features.

### 📊 Datasets
- **Source:** [Kaggle - Smartphones Price Dataset](https://www.kaggle.com/datasets/juanmerinobermejo/smartphones-price-dataset/data)
- **Type:** CSV file
- **License:** Apache 2.0

### Dataset Features:
1. **Smartphone Name**: Unique identifier or model name.
2. **Brand**: Brand of the smartphone.
3. **Model**: Model of the smartphone.
4. **RAM**: Random Access Memory (GB).
5. **Storage**: Internal storage capacity (GB).
6. **Color**: Color of the smartphone.
7. **Free**: Whether the phone is attached to a mobile carrier contract (Yes/No).
8. **Price**: The price of the smartphone in the respective currency.

---

## Project Workflow:

### Step 1: Data Acquisition and Basic Insights
- Import the dataset and explore it to gain insights into the data structure and any missing values.

### Step 2: Data Preprocessing
- Handling missing values.
- Encoding categorical variables (`Brand`, `Color`, `Free`).
- Scaling and normalizing continuous variables like `RAM`, `Storage`, and `Price`.

### Step 3: Exploratory Data Analysis (EDA)
- Visualize relationships between features.
- Perform statistical analysis on feature distributions.
- Analyze feature correlations to understand their impact on price prediction.

### Step 4: Machine Learning Models
This project applies the following machine learning models:
1. **Multiple Linear Regression**
2. **Polynomial Regression**
3. **Ridge Regression**
4. **RandomForestRegressor**
5. **XGBRegressor**

### Step 5: Model Evaluation
- Evaluation metrics: **R-squared** and **Mean Absolute Error (MAE)**.
- Perform cross-validation to assess model generalizability.

### Step 6: Hyperparameter Tuning
- Use grid search and random search to fine-tune the models for improved accuracy.

### Step 7: Model Selection
- Select the best-performing model based on evaluation metrics for final predictions.

These models are evaluated based on how accurately they predict smartphone prices.

---

## How to Use:

1. Clone the repository and install necessary dependencies.
2. Open the Jupyter Notebook file `SmartPhonesPrediction-Final.ipynb`.
3. Run the notebook cells to execute the complete pipeline of data preprocessing, model training, and evaluation.

---

## Results:
The best-performing model, based on evaluation metrics, is selected for predicting smartphone prices.
XGBoost and Random Forest showed strong performance in price prediction due to their robustness.

## Future Work:
Expand the dataset with more smartphone models and brands.
Improve feature engineering to capture more relevant smartphone characteristics.
Explore deep learning models for better predictive performance.

## License:
This project uses data provided under the Apache 2.0 License from Kaggle.

## Acknowledgments:
Dataset provided by Kaggle, available under the Apache 2.0 License.
