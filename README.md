# 🏡 House Price Prediction using Machine Learning

A Machine Learning project that predicts house prices based on property characteristics using regression techniques. This project demonstrates an end-to-end machine learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and feature importance analysis using Python and Scikit-learn.

---

## 📌 Project Overview

House price prediction is one of the most common real-world regression problems in Machine Learning. In this project, a predictive model is developed to estimate residential property prices using features such as house area, number of bedrooms, bathrooms, floors, waterfront availability, property view, and location.

The project covers the complete data science pipeline—from data exploration and preprocessing to model building and performance evaluation.

---

## 🎯 Objectives

- Understand the housing dataset through exploratory data analysis.
- Clean and preprocess the data for machine learning.
- Analyze the relationship between house features and price.
- Train a regression model for accurate house price prediction.
- Evaluate model performance using standard regression metrics.
- Identify the most influential features affecting house prices.

---

## 📂 Dataset

**Dataset:** `House_data.csv`

The dataset contains residential property information used for predicting house prices.

| Feature | Description |
|---------|-------------|
| Price | Target variable representing the house price |
| Bedrooms | Number of bedrooms |
| Bathrooms | Number of bathrooms |
| Area | Area of the house (square feet) |
| Floors | Number of floors |
| Waterfront | Indicates whether the property has a waterfront view (0 = No, 1 = Yes) |
| View | Property view rating |
| Location | Geographic location of the property |

---

## 🛠 Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Exploratory Data Analysis (EDA)

The project includes:

- Dataset inspection
- Statistical summary
- Correlation analysis
- Distribution analysis
- Scatter plots
- Outlier detection
- Relationship analysis between features
- Feature importance visualization

---

## ⚙️ Data Preprocessing

The following preprocessing steps were performed:

- Data cleaning
- Handling categorical variables
- Label encoding
- Outlier detection and removal
- Feature selection
- Train-test split

---

## 🤖 Machine Learning Workflow

1. Import Libraries
2. Load Dataset
3. Data Cleaning
4. Exploratory Data Analysis
5. Feature Engineering
6. Data Preprocessing
7. Train-Test Split
8. Model Training
9. Model Evaluation
10. Feature Importance Analysis

---

## 📈 Model Evaluation

The model was evaluated using standard regression metrics:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics help assess the prediction accuracy and overall performance of the regression model.

---

## 📸 Project Visualizations

### 📊 Correlation Heatmap

Shows the relationship between numerical variables.

![Correlation Heatmap](images/correlation_heatmap.png)

---

### 📈 House Price Distribution

Displays the distribution of house prices.

![House Price Distribution](images/house_price_distribution.png)

---

### 🏠 Area vs House Price

Illustrates the relationship between property area and selling price.

![Area vs Price](images/area_vs_price.png)

---

### 🎯 Regression Results

Comparison between actual and predicted house prices.

![Regression Results](images/regression_results.png)

---

### 📉 Residual Plot

Shows prediction errors and helps evaluate model performance.

![Residual Plot](images/residual_plot.png)

---

### 📋 Feature Importance

Displays the contribution of each feature to the prediction model.

![Feature Importance](images/feature_importance.png)

---

## 📁 Project Structure

```
House-Price-Prediction/
│
├── House_Price_Prediction.ipynb
├── House_data.csv
├── README.md
├── requirements.txt
├── .gitignore
│
└── images/
    ├── correlation_heatmap.png
    ├── house_price_distribution.png
    ├── area_vs_price.png
    ├── regression_results.png
    ├── residual_plot.png
    └── feature_importance.png
```

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/Bhavyashree08S/House-Price-Prediction.git
```

### Navigate to the Project

```bash
cd House-Price-Prediction
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Notebook

Open:

```
House_Price_Prediction.ipynb
```

using Jupyter Notebook or Google Colab.

---

## 💡 Future Enhancements

- Hyperparameter tuning
- Cross-validation
- Compare multiple regression algorithms
- Deploy the model using Streamlit
- Build a Flask-based prediction web application
- Integrate real-time user input for predictions

---

## 🧠 Skills Demonstrated

- Data Cleaning
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Feature Engineering
- Machine Learning
- Regression Analysis
- Model Evaluation
- Feature Importance Analysis
- Python Programming

---

## 📜 Conclusion

This project demonstrates an end-to-end machine learning pipeline for predicting house prices using regression techniques. Through data preprocessing, exploratory data analysis, feature engineering, model training, and evaluation, the project provides valuable insights into the factors influencing residential property prices while showcasing practical machine learning and data analysis skills.

---

## 👩‍💻 Author

**Bhavyashree**

MCA Graduate | Data Science & Analytics Enthusiast

📧 Open to opportunities in Data Analytics, Data Science, and Machine Learning.

- GitHub: https://github.com/Bhavyashree08S
- LinkedIn: https://www.linkedin.com/in/bhavyashree-doomappa-jayasheela-a51755326/

---

⭐ If you found this project helpful, consider giving it a **Star**!
