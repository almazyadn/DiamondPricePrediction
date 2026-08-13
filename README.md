# 💎 Diamond Price Prediction (Machine Learning)

## 📌 Project Overview
This project was developed as part of the IT 461: Principles of Machine Learning course at King Saud University. The goal of this project is to build a machine learning model capable of accurately predicting the price of a diamond based on its physical attributes. 

Diamond valuation is a complex process influenced by multiple factors, most prominently the "Four Cs" (Carat, Cut, Color, and Clarity), alongside structural dimensions (x, y, z, depth, and table).

## 🛠️ Technologies Used
* **Language:** Python
* **Environment:** Jupyter Notebook
* **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn
* **Techniques:** Data Preprocessing, Exploratory Data Analysis (EDA), Regression Modeling, Feature Engineering

## 📂 Repository Structure
* `Diamond_Price_Prediction.ipynb`: The main Jupyter Notebook containing the full pipeline—from exploratory data analysis (EDA) and data preprocessing to model training and evaluation.
* `/data`: Contains the original `diamonds.csv` and the cleaned `Preprocessed_datasets.csv`.
* `/docs`: Contains the comprehensive academic project report and the final presentation slides detailing our methodology and model evaluations.

## 📊 Dataset
The dataset includes features such as:
* **Numerical Features:** Carat, Depth, Table, X (length), Y (width), Z (depth).
* **Categorical Features:** Cut, Color, Clarity.
* **Target Variable:** Price (in USD).

## 💡 Key Results & Methodology
1. **Data Preprocessing:** Handled categorical variables using encoding and scaled numerical features to optimize model performance.
2. **Exploratory Data Analysis (EDA):** Visualized feature distributions and correlation matrices to identify relationships between the "Four Cs" and the price.
3. **Modeling:** Trained and evaluated multiple regression models to predict prices with high accuracy, optimizing hyperparameters for the best-performing algorithm.
4. **Conclusion:** Identified Carat and dimensional measurements as the most significant predictors of a diamond's market price.

---
*Group Members: Najla Almazyad, Jood Alkhrashi, Sara Aloqiel, Nouf Almansour*
