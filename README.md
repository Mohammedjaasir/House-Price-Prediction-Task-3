# 🏠 House Price Prediction - Linear Regression (Task 3)

> This project implements **Simple** and **Multiple Linear Regression** using Scikit-Learn on a housing dataset to predict property prices. It's part of the AI & ML Internship Task 3 and aims to demonstrate model implementation, evaluation, and interpretation with clarity and confidence.

---

## 📁 Dataset
- Source: [Housing Price Prediction Dataset (Kaggle)](https://www.kaggle.com/datasets/harishkumardatalab/housing-price-prediction)
- Target: `price` (House selling price)
- Features: Area, bedrooms, bathrooms, mainroad access, furnishing status, and more

---

## 🎯 Objectives
- Understand and implement both **Simple** and **Multiple Linear Regression**
- Preprocess and encode data appropriately
- Evaluate models using MAE, MSE, and R²
- Interpret the model coefficients and visualize the regression line

---

## 🧰 Tools & Libraries
| Tool            | Purpose                        |
|------------------|-------------------------------|
| Python           | Programming Language          |
| Pandas           | Data Handling                 |
| Matplotlib, Seaborn | Visualization               |
| Scikit-learn     | ML Algorithms & Evaluation    |

---

## 🔄 Workflow

1. **Data Loading & Exploration**
    - Checked for nulls and basic stats
    - Visualized distributions and relationships

2. **Preprocessing**
    - Filled/removed null values
    - One-hot encoded categorical variables

3. **Simple Linear Regression**
    - Used `area` as a single feature to predict `price`
    - Plotted regression line for better understanding

4. **Multiple Linear Regression**
    - Used all numerical + encoded features
    - Trained and evaluated the model

5. **Evaluation**
    - Compared models using:
        - Mean Absolute Error (MAE)
        - Mean Squared Error (MSE)
        - R² Score

---

## 📈 Key Visuals

- 📊 Regression Line for Simple Linear Regression  
- 🔥 Heatmap of Feature Correlation  
- 🧩 One-hot Encoded Feature View  
- 🎯 R² Score showing model accuracy

---

## 💡 Key Insights
- Area was a strong predictor of price in simple regression.
- Multiple regression captured more complexity using additional features like bedrooms, furnishing, etc.
- One-hot encoding allowed us to use categorical values effectively.
- R² improved significantly from simple to multiple regression.

---

## 📂 Project Structure

📁 LinearRegression_Housing
│
├── housing.csv # Dataset
├── LinearRegression_EDA.ipynb # Main notebook
├── README.md # This file

---

## 🚀 How to Run
1. Clone this repo
2. Install dependencies:  
   `pip install pandas scikit-learn matplotlib seaborn`
3. Run the notebook:  
   `LinearRegression_EDA.ipynb`

---

## ✨ Final Note
This project focuses on **clarity, analysis, and interpretation**, not just code. Linear regression is simple in theory — this notebook makes it **understandable in practice**.
"""

