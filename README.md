# 🏡 House Price Prediction Using Linear Regression  

## 📌 Overview  
This project demonstrates the implementation of a **Simple Linear Regression** model to predict house prices based on their size (sq ft).  
It is built using **Python, Pandas, Scikit-learn, and Matplotlib**, making it a great introductory project for machine learning enthusiasts.  

## 🚀 Features  
- **Data Processing**: Load and clean a dataset of house sizes and prices.  
- **Model Training**: Train a linear regression model using Scikit-learn.  
- **Performance Evaluation**: Calculate MAE, MSE, and RMSE for model accuracy.  
- **Data Visualization**: Plot the dataset and regression line for better understanding.  

---

## 📂 Project Structure  

---

## 🛠 Technologies Used  
- **Python** 🐍  
- **Pandas** 🏗️ - For data manipulation  
- **NumPy** 🔢 - For numerical computations  
- **Scikit-learn** 🤖 - For machine learning modeling  
- **Matplotlib** 📊 - For data visualization  

---

## 📊 Dataset Information  
The dataset (`house_prices.csv`) contains the following columns:  

| Column         | Description                          |  
|---------------|--------------------------------------|  
| `Size (sq ft)` | The size of the house in square feet |  
| `Price ($1000s)` | The price of the house in thousands of dollars |  

---

## 📌 Installation & Usage  

### **🔹 1. Clone the Repository**  
```bash
git clone https://github.com/your-username/house-price-prediction.git
cd house-price-prediction
```
📈 Model Performance
After training the model, it is evaluated using three key metrics:

Metric	Description:
MAE (Mean Absolute Error)	Measures average absolute error
MSE (Mean Squared Error)	Penalizes larger errors more heavily
RMSE (Root Mean Squared Error)	Provides an interpretable error metric

✅ Example Output:
Mean Absolute Error: 10.5  
Mean Squared Error: 175.3  
Root Mean Squared Error: 13.24  
📊 Visualization
The model's performance is illustrated using a scatter plot of actual vs. predicted values:


🔵 Blue Dots → Actual data points

🔴 Red Line → Predicted regression line

🛠️ Future Enhancements
✅ Add multiple regression for better accuracy
✅ Include more features (e.g., location, number of rooms)
✅ Use polynomial regression for nonlinear trends

🤝 Contributing
Contributions are welcome! To contribute:

Fork the repository

Create a new branch (feature-improvement)

Commit your changes

Submit a pull request
