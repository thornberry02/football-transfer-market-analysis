# Football Transfer Market Analysis

This project investigates data from the football transfer market, focusing on how player **market value** and **age** influence final **transfer fees**.  
The analysis uses **regression trees in R** to model predictive relationships and evaluate model accuracy.

---

## 📊 Dataset
- Source: [Top 250 Football Transfers (Kaggle)](https://www.kaggle.com/datasets/vardan95ghazaryan/top-250-football-transfers-from-2000-to-2018)
- Data covers transfers from the **2000/2001** to **2018/2019** seasons.
- Focused on Europe’s **top 5 leagues** after initial data cleaning.

---

## 🧠 Objectives
- Examine whether **Market Value** can predict a player’s transfer fee.
- Test **Age** as a predictor variable.
- Combine both factors (Age + Market Value) to compare model performance.

---

## 🧮 Methods
- Regression Tree models built using R.
- Pruning applied using optimal `cp` (complexity parameter) values.
- Model evaluation based on **Mean Squared Error (MSE)**.
- Comparison made with previous logistic regression model.

---

## 📈 Key Findings
- **Market Value alone** was not a strong predictor (high MSE).  
- **Age** had a stronger relationship with transfer fee (negative correlation ≈ -0.6).  
- Combining **Age and Market Value** improved model performance significantly.  
- Regression trees provided deeper insight compared to logistic regression.

---

## 🧰 Tools & Skills
- **R (rpart, tidyverse, ggplot2)**  
- **Regression Trees, Model Pruning, Prediction, Data Cleaning**

---

## ✍️ Author
**Cian Thornberry**  
📍 Waterford, Ireland  
📧 [thornberry02@gmail.com](mailto:thornberry02@gmail.com)  
🔗 [LinkedIn](https://www.linkedin.com/in/cian-thornberry-6a01422b5)


