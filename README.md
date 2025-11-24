### 🛒 MarketPriceX  
### Amazon ML Challenge 2025 — Product Price Prediction Model

MarketPriceX is a machine learning solution developed for the **Amazon ML Challenge 2025**, aimed at predicting optimal product prices using product descriptions and attributes. The model analyzes text-based and structured product metadata to estimate a competitive and realistic price point for marketplace use.

---

## 🚀 Overview

In e-commerce, pricing accuracy directly impacts customer trust, conversions, and marketplace optimization. The challenge required building a predictive model capable of analyzing product descriptions holistically and estimating the product’s optimal price.

This repository contains all code, notebooks, documentation, and results related to the challenge submission.

---

## 🎯 Problem Statement

In e-commerce, determining the optimal price point for products is crucial for marketplace success and customer satisfaction.  
Your challenge is to develop an ML solution that analyzes product details and predicts the price of the product.  

The relationship between product attributes and pricing is complex — with factors like brand, specifications, product quantity, and product descriptions directly influencing pricing.  

Your task was to build a model that can analyze these product details holistically and suggest an optimal price.

---

## 📂 Repository Structure

MarketPriceX/
│
├── data/ # placeholder for raw and processed data (not included)
├── notebooks/ # Jupyter notebooks for EDA, preprocessing, training, evaluation
├── results/ # plots, metrics, trained model outputs
├── miscellaneous/ # notebooks that I created while learning and experimenting on a completely different problem statement 
└── README.md # project documentation

---

## 🧠 Approach

The project followed a complete machine learning workflow:

### **1. Exploratory Data Analysis (EDA)**
- Inspected category distribution, missing values, and textual patterns  
- Identified brand frequency patterns  
- Analyzed price distribution and outliers  

### **2. Data Cleaning**
- Removed noise and irrelevant symbols using regex  
- Standardized numerical fields  
- Handled missing values  
- Normalized product description fields  

### **3. Feature Engineering**
- Label Encoding for categorical attributes  
- Extracted keyword-based features from product descriptions  
- Generated text length metrics and product attribute signals  
- Added brand-related and quantity-based derived features  

### **4. Model Selection**
Evaluated multiple ML models:
- Linear Regression  
- Random Forest  
- Gradient Boosting  
- **XGBoost (selected)**  

### **5. Model Tuning**
- Hyperparameter optimization using randomized search  
- Regularization tuning for better generalization  
- Adjusted learning rate, depth, subsampling, and feature ratios  

---

## 🏆 Results

SMAPE Improvement ↑ - 13% better than the baseline model

---

## 🛠 Tech Stack

**Languages & Tools:**  
- Python  
- Excel  

**Libraries Used:**  
- NumPy  
- Pandas  
- Regex  
- Scikit-learn  
- SciPy  
- XGBoost  
- Jupyter Notebook  

---

## ▶️ How to Run the Project

This project is entirely notebook-driven.  
Open the Jupyter notebook inside the `notebooks/` folder.

To install dependencies:

```bash
pip install numpy pandas scikit-learn scipy xgboost
then Then simply run all cells in each notebook.
