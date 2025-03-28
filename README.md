# 🔌 Energy Consumption Regression – Appliances Dataset

This notebook continues from Assignment 1A to build improved regression models for predicting appliance energy consumption based on weather/environmental factors.

---

## 📄 Dataset
- `energydata_complete.csv`  
- Sourced from UCI ML Repository, includes 29 variables such as T1-T9 (temperature sensors), RH1-RH9 (humidity), light, visibility, and appliances energy use.

---

## 🛠 Tools & Libraries
- Python  
- pandas, seaborn, matplotlib  
- scikit-learn  
- Linear Regression, Lasso, Ridge, Random Forest

---

## 🧠 Project Highlights
- Feature selection using correlation, mutual information  
- StandardScaler, polynomial features, and one-hot encoding  
- Regression models: Linear, Lasso, Ridge, RF  
- Evaluation using RMSE, R², cross-validation  
- Visualization of predictions vs. actual usage

---

## 📁 Files
- `assign1b.ipynb` – Main analysis notebook  
- `energydata_complete.csv` – Raw dataset  

---

## 📊 Results
- Best model: Random Forest Regressor  
- R²: ~0.54  
- RMSE: ~91.4  

---

## ✅ Future Improvements
- Hyperparameter tuning (GridSearchCV)  
- Ensemble stacking  
- Feature importance visualization with SHAP  

---

## 👤 Author
Aditya Venugopalan Nediyirippil  
GitHub: [a1899824-aditya](https://github.com/a1899824-aditya)
