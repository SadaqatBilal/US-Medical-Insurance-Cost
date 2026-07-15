# 📊 U.S. Medical Insurance Costs Analysis

## 📝 Project Overview
This project analyzes a dataset of medical insurance charges in the United States. The goal is to explore how different factors — such as age, sex, BMI, smoking status, region, and number of children — influence the total insurance costs.

This project was completed using Python, applying concepts like file handling, data structures, loops, functions, and basic statistical calculations.

---

## 🛠️ Tools & Technologies Used
- Python 3
- `csv` module for reading and processing data
- Custom functions for calculations and comparisons
- No external libraries required

---

## 📈 Dataset Information
The dataset (`insurance.csv`) contains the following columns:
- `age`: Age of the primary beneficiary
- `sex`: Gender of the beneficiary
- `bmi`: Body Mass Index (a measure of body fat)
- `children`: Number of dependents covered by insurance
- `smoker`: Whether the person is a smoker or non-smoker
- `region`: Geographic area in the U.S.
- `charges`: Total annual medical insurance costs

---

## 📊 Analysis Results

### 1. Basic Dataset Summary
- **Average Age:** 39.21 years
- **Average BMI:** 30.66
- **Average Insurance Charge:** $13,270.42

---

### 2. Impact of Smoking Status
- **Average charge for smokers:** $32,050.23
- **Average charge for non-smokers:** $8,434.27
- **Difference:** $23,615.96 higher for smokers

---

### 3. Impact of Gender
- **Average charge for males:** $13,956.75
- **Average charge for females:** $12,569.58

---

### 4. Variation by Region
- **Southwest:** $12,346.94
- **Southeast:** $14,735.41 (highest average)
- **Northwest:** $12,417.58
- **Northeast:** $13,406.38

---

### 5. Impact of Number of Children
- **0 children:** $12,365.98
- **1 child:** $12,731.17
- **2 children:** $15,073.56
- **3 children:** $15,355.32
- **4 children:** $13,850.66
- **5 children:** $8,786.04 (lowest average)

---

## 💡 Key Conclusions
1. **Smoking is the biggest factor:** Smokers pay nearly 4 times more on average than non-smokers.
2. **Gender has a small effect:** Males have slightly higher average charges than females, but the difference is not large.
3. **Regional differences exist:** The Southeast region has the highest average insurance costs.
4. **Number of children affects costs moderately:** Charges increase up to 3 children, then begin to decrease for 4 or 5 children.

---

## 📂 Project Files
- `insurance.csv` – Raw dataset
- `insurance_analysis.py` – Python code for loading, processing, and analyzing data
- `README.txt` – Project documentation

---

## ✅ Skills Demonstrated
- Reading and writing data from CSV files
- Cleaning and converting data types
- Writing reusable functions
- Performing statistical calculations
- Comparing groups and identifying trends
- Presenting results clearly
