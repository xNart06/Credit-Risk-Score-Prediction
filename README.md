# Credit Risk Score Calculation with Regression Model

<p align="center">
  <a href="https://pandas.pydata.org/">
    <img src="https://img.shields.io/badge/Pandas-1.x-blue?logo=pandas&logoColor=white" alt="Pandas">
  </a>
  <a href="https://scikit-learn.org/">
    <img src="https://img.shields.io/badge/Scikit--Learn-0.24-green?logo=scikit-learn&logoColor=white" alt="Scikit-Learn">
  </a>
  <a href="https://matplotlib.org/">
    <img src="https://img.shields.io/badge/Matplotlib-3.x-orange?logo=matplotlib&logoColor=white" alt="Matplotlib">
  </a>
  <a href="https://docs.python.org/3/library/tkinter.html">
    <img src="https://img.shields.io/badge/Tkinter-Built--in-yellow?logo=tkinter&logoColor=white" alt="Tkinter">
  </a>
</p>


<p align="center">
  <a href="README.md">
    <img src="https://img.shields.io/badge/lang-English-blue.svg" alt="English">
  </a>
  <a href="README_TR.md">
    <img src="https://img.shields.io/badge/lang-Turkish-red.svg" alt="Turkish">
  </a>
</p>

## About the Project

This project aims to develop a regression model to calculate credit risk scores for bank customers by analyzing their financial data. The model uses data such as salary, credit limits, and account balances to make predictions, optimizing the credit evaluation processes of banks.

---

## Goals 📋

1. **Accurate Credit Risk Score Calculation**: Predict risk scores using customers' financial data.
2. **Optimization**: Improve the credit evaluation processes of banks.
3. **Machine Learning Models**: Use regression models such as **RandomForest** and **LinearRegression**.

---

## Workflow

### 1. **Data Preprocessing**
- Using the `Loan.csv` dataset from Kaggle:
  - Reading data
  - Extracting statistics
  - Detecting null values
  - Determining data types
  - Identifying unique values
  - Dropping unnecessary columns
  - Applying `LabelEncoder` to object values
  - Splitting target variable

### 2. **Model Training**
- Train models with **RandomForestRegressor** and **LinearRegression**.
- Evaluate the models using metrics like **R² score** and **Mean Squared Error (MSE)**.

### 3. **Metric Generation**
- After working with both models, the RandomForestRegressor model was chosen. Below are the visualizations for the metrics.
### RandomForest:
<img src="images/RandomForest.png" alt="RandomForest">
<img src="images/RandomMetric.png" alt="RandomMetric">

### Linear:

<img src="images/Linear.png" alt="Linear">
<img src="images/LinearMetric.png" alt="LinearMetric">

### 4. **Interface Development and Result**
- Create an interface using **Tkinter** where customers can input their data and view the prediction results.
- Perform prediction tests with the model.
- The values used in these tests are held separate from the training dataset.

### First Test:
<img src="images/Pred1.jpg" alt="Pred1">
<img src="images/Pred1_1.jpg" alt="Pred1_1">

### Second Test:

<img src="images/Pred2.jpg" alt="Pred2">
<img src="images/Pred2_2.jpg" alt="Pred2_2">

## Dataset 📂

The dataset is available on Kaggle:  

<p align="left">
  <a href="https://www.kaggle.com/datasets/lorenzozoppelletto/financial-risk-for-loan-approval">
    <img src="images/Kaggle_logo.png" alt="Kaggle Logo" width="200">
  </a>
</p>

The `Loan.csv` file is located in the `dataset/` folder.

---

## Technologies Used 🛠️
- **Python** - Main programming language
- **Pandas** - Data manipulation
- **Scikit-Learn** - Machine learning
- **Matplotlib** - Visualization
- **Tkinter** - Interface development

---

## Developers 👨‍💻

- **Furkan Hamza BOLAT**  
  **Email:** [furkanhamzabolat@gmail.com](mailto:furkanhamzabolat@gmail.com)  

- **Furkan DAYI**  
  **Email:** [furkan.dyi@hotmail.com](mailto:furkan.dyi@hotmail.com)
