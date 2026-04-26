# 🚗 Car Price Prediction

## 📌 Project Overview

This project focuses on predicting the selling price of used cars using Machine Learning techniques.
A regression model is trained on historical car data to estimate prices based on features such as year, fuel type, transmission, and more.

---

## 📊 Dataset

* File: `car data.csv`
* Contains information about used cars including:

  * Year of purchase
  * Present Price
  * Kilometers Driven
  * Fuel Type
  * Seller Type
  * Transmission
  * Owner

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## 🚀 Project Workflow

1. Data Loading and Exploration
2. Data Cleaning and Preprocessing
3. Handling Categorical Variables (Label Encoding)
4. Feature Selection
5. Model Training using Random Forest Regressor
6. Model Evaluation

---

## 📈 Results

* Achieved high prediction accuracy using Random Forest

* Evaluation Metrics:

  * R² Score (Good fit between actual and predicted values)
  * Mean Squared Error (Low error rate)

* Visualization:

  * Actual vs Predicted Price Scatter Plot

---

## 🔍 Sample Prediction

The model can predict car prices for new input data.

Example:

* Input → Car features from dataset
* Output → Predicted selling price

---

## ▶️ How to Run

1. Install required libraries:

```
pip install pandas numpy matplotlib seaborn scikit-learn
```

2. Run the notebook:

```
jupyter notebook car_price.ipynb
```

3. Execute all cells to see results

---

## 📁 Project Structure

```
CodeAlpha_CarPricePrediction/
│
├── car data.csv
├── car_price.ipynb
├── README.md
└── requirements.txt
```

---

## 🎯 Conclusion

This project demonstrates how machine learning can be used for real-world price prediction problems.
The Random Forest model provides accurate and reliable predictions, making it suitable for practical applications.

---

## 🔗 Author

Prem Kumar
