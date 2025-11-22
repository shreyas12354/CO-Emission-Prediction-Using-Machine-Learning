![rsz_1car-emitting-carbon-dioxide-co2-environmental-vector-21630081](https://user-images.githubusercontent.com/65482013/83296928-3ecc3180-a20f-11ea-94c1-a3ace3ad0d21.jpg)

# **CO₂ Emission Prediction Using Machine Learning**

This project analyzes vehicle fuel consumption data and builds machine-learning models to **predict CO₂ emissions** based on features such as engine size and fuel consumption.  
The dataset comes from the Government of Canada’s open data portal.

---

## 📁 **Repository Structure**

.
├── CO2_analysis.ipynb # Full EDA + regression models + plots
├── CO2_analysis_report.pdf # Polished report with insights & visuals
├── Simple_Linear_Regression_Model.ipynb
├── MultipleLinearRegressionModel.ipynb
├── PolynomialRegressionModel.ipynb
├── FuelConsumptionCo2.csv # Dataset
└── README.md # Project documentation



---

## 📊 **Dataset Description**

The dataset contains details of light-duty vehicles sold in Canada, with features like:

- **Engine Size (L)**
- **Cylinders**
- **Fuel Consumption (City, Highway, Combined)**
- **Transmission Type**
- **Vehicle Class**
- **CO₂ Emissions (g/km)** → Target variable

---

## 🔍 **Key Analysis Performed**

### **Exploratory Data Analysis (EDA)**  
- Distribution of engine size & CO₂ emissions  
- Outlier checks  
- Pairwise correlations  
- Heatmap of numerical features  

### **Feature Insights**
- Strongest predictor of CO₂ emissions: **Fuel Consumption (Combined)**  
- Engine Size and Cylinders also show strong positive correlation  
- Transmission type has weak correlation  

---

## 💡 **Why Use Linear Regression?**

Even though the relationship isn’t perfectly linear:

- CO₂ emissions increase steadily with engine size & fuel consumption  
- Scatter plots indicate a general linear trend  
- Linear Regression provides a **strong baseline** because it is:
  - Simple  
  - Interpretable  
  - Performs surprisingly well on this dataset  

Polynomial regression is also tested for capturing mild non-linear patterns.

---

## 🤖 **Models Implemented**

### ✔ **1. Simple Linear Regression**  
Predict CO₂ using **Engine Size** alone.

### ✔ **2. Multiple Linear Regression**  
Uses:
- Engine Size  
- Fuel Consumption (Combined)

Produces a better fit with higher R² and lower RMSE.

### ✔ **3. Polynomial Regression (Degree 2)**  
Captures curvature in the data and slightly improves performance.

---

## 📈 **Visualizations Included**

- CO₂ vs Engine Size scatter plot  
- Polynomial regression curve  
- Correlation heatmap  
- Residual distribution  
- Feature correlation rankings  

All visuals are included in both:
- The **notebook**, and  
- The **PDF report**

---

## 📝 **Conclusion**

- **Fuel consumption metrics** are the strongest predictors of CO₂ emissions.  
- Linear models perform well and explain most variance.  
- Polynomial regression improves performance slightly but adds complexity.  
- The dataset is ideal for demonstrating regression techniques.

---

## 🛠 **Technologies Used**

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Scikit-Learn  
- Jupyter Notebook  

---
