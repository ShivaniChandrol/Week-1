# Week 2 Task 

## Project: Electric Vehicle Range Prediction using Linear Regression

In this task, I built a **machine learning model** to predict the **range (in km)** of electric vehicles based on specifications like **battery capacity, power, and torque**.

---

### Steps Followed

1. **Loaded Dataset** — Imported the EV dataset from Kaggle.  
2. **Data Exploration** — Checked structure, info, and descriptive statistics.  
3. **Data Cleaning** — Handled missing values by dropping null entries.  
4. **Feature Selection** — Selected `Battery Capacity (kWh)`, `Power (hp)`, and `Torque (Nm)` as features.  
5. **Model Training** — Trained a Linear Regression model using `train_test_split`.  
6. **Model Evaluation** — Evaluated using metrics:  
   - MAE (Mean Absolute Error)  
   - RMSE (Root Mean Squared Error)  
   - R² Score  

---

### Results Summary

| Metric | Value |
|--------|--------|
| **Model Used** | Linear Regression |
| **R² Score** | 0.82 |
| **MAE** | 45.23 |
| **RMSE** | 60.18 |


---

### Colab Notebook

[🔗 Click here to open in Google Colab](https://colab.research.google.com/drive/16liE3hcHvWY5gthd_k48Pc6YqrAov18r)

---

### Key Learning

- Understood how **Linear Regression** predicts continuous values.  
- Learned to **split data** into train and test sets.  
- Practiced evaluating model performance with **statistical metrics**.

---

*This project is part of Week 2 of my Machine Learning learning journey.*
