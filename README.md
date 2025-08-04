# 💰 Health Cost Predictor

A simple machine learning project that predicts medical insurance costs based on personal information such as age, BMI, region, and smoking status.

## 📌 Project Goal

Use regression techniques to predict healthcare costs from tabular data.  
The project passes evaluation if the Mean Absolute Error (MAE) is less than **$3500**.  
✅ **Achieved MAE: ~2365**

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib / Seaborn
- Google Colab

## 📊 Features

- Preprocessing (one-hot encoding + polynomial features)
- Regression model using `RandomForestRegressor`
- Data visualization (actual vs predicted expenses)
- MAE evaluation for model performance

## 📁 Dataset

Dataset used:  
[insurance.csv](https://raw.githubusercontent.com/stedy/Machine-Learning-with-R-datasets/master/insurance.csv)

Features:

- `age`: Age of the individual  
- `sex`: Gender  
- `bmi`: Body mass index  
- `children`: Number of children  
- `smoker`: Whether the person smokes  
- `region`: US region  
- `charges`: Medical expenses (target)

## 📷 Result Preview

![Prediction Graph](https://via.placeholder.com/600x300?text=Graph+Placeholder)  
*(Add screenshot from Colab if you'd like)*

## 🚀 How to Run

1. Open the notebook in [Google Colab](https://colab.research.google.com/)
2. Run all cells
3. Modify or test with new data!

---

⭐️ Created as part of the [freeCodeCamp Machine Learning Curriculum](https://www.freecodecamp.org/)
