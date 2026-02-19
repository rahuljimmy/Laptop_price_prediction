# 💻 Laptop Price Prediction using Machine Learning

## 📌 Project Overview

The Laptop Price Prediction project is a Machine Learning application that predicts the price of a laptop based on its specifications. Users can input laptop configurations such as brand, RAM, processor, storage, GPU, operating system, and weight, and the model will estimate the laptop's price.

This project demonstrates the complete Machine Learning lifecycle, including data preprocessing, feature engineering, model training, evaluation, and deployment.

---

## 🎯 Project Objective

The main objective of this project is to build an accurate Machine Learning model that can predict laptop prices based on various hardware and software features, and deploy the model using Streamlit for real-time predictions.

---
                                                                                                   
## 📊 Dataset Information

The dataset contains various laptop configurations and their corresponding prices.

### Features include:

- Company (Brand)
- TypeName
- RAM
- Weight
- CPU
- GPU
- Operating System
- Storage (HDD/SSD)
- Screen Resolution
- Inches (Screen Size)
- Price (Target Variable)

---

## 🧠 Machine Learning Workflow

The following steps were performed in this project:

1. Data Collection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Model Training
6. Model Evaluation
7. Hyperparameter Tuning
8. Model Selection
9. Model Deployment using Streamlit

---

## 🤖 Machine Learning Models Used

The following models were tested:

- Linear Regression
- K-Nearest Neighbours Regressor
- Support Vector Regressor
- Decision Tree Regressor
- Random Forest Regressor
- Voting Regressor
- Stacking Regressor
- XGBoost Regressor

### 📈 Best Performing Model:
Random Forest Regressor was selected based on its superior performance.  
R² Score = 90%    
Mean Absolute Error (MAE) = 8750 INR

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Streamlit
- Pickle
- Git
- GitHub

---

## 📂 Project Structure

```
Laptop-Price-Prediction
│
├── data
│   └── laptop_data.csv
│
├── notebooks
│   └── Laptop_Price_Prediction.ipynb
│
├── model
│   └── model.pkl
│
├── app.py
│
├── requirements.txt
│
└── README.md
```

---

## ⚙️ How to Run This Project

### Step 1: Clone the repository

```
git clone https://github.com/rahuljimmy/Laptop_price_prediction.git
```

### Step 2: Navigate to the project directory

```
cd Laptop-Price-Prediction
```

### Step 3: Install the required libraries

```
pip install -r requirements.txt
```

### Step 4: Run the Streamlit application

```
streamlit run app.py
```

---

## 🚀 Features of This Project

- End-to-end Machine Learning project
- Real-world dataset
- Multiple model training and comparison
- Best model selection
- Model deployment using Streamlit
- User-friendly interface for predictions

---

## 💡 Use Case

This project can be useful for:

- Customers to estimate laptop prices
- Students to learn Machine Learning deployment
- Beginners to understand end-to-end ML workflow
- Portfolio project for Data Scientist / Machine Learning Engineer roles

---

## 👨‍💻 Author

Rahul Jimmy

Aspiring Data Scientist

---

## ⭐ Support

If you like this project, please consider giving it a star ⭐ on GitHub.




