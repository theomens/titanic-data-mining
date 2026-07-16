# BCS 402 - Data Mining and Warehousing  
## Practical Mid-Semester Examination

**Accra Technical University**  
**Computer Science Department (BTECH)**

### Student Information
- **Name:** Theophilus Mensah  
- **Student ID:** 01250686B

---

### Project Overview
This project performs **Exploratory Data Analysis (EDA)** and builds a **Stacking Ensemble Machine Learning Model** on the Titanic dataset to predict passenger survival. The solution addresses all required tasks (1–11) as specified in the examination paper.

### Objectives
- Conduct thorough EDA using Python (Pandas, NumPy, Matplotlib, Seaborn)
- Develop a stacking model that performs better than traditional single models
- Provide detailed interpretations and visualizations
- Explain model evaluation using Confusion Matrix and key metrics

### Key Insights from EDA
1. **Gender** is a strong predictor — Females had significantly higher survival rates.
2. **Passenger Class (Pclass)** — 1st class passengers had much higher survival chances.
3. **Age** — Children had higher survival priority.
4. **Fare** contains outliers which were identified and considered during analysis.
5. Feature engineering (e.g., Title, FamilySize, IsAlone) improves model performance.

### Model Implemented
- **Stacking Ensemble Model**
  - Base Learners: Random Forest + Gradient Boosting
  - Meta Learner: Logistic Regression
- This ensemble approach combines the strengths of multiple models for better accuracy and robustness.

### Technologies Used
- Python
- Google Colaboratory
- Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

### Files Included
- `Titanic_EDA_Stacking.ipynb` → Main Colab Notebook
- `train.csv` → Titanic Dataset (downloaded from Kaggle)

### How to Run
1. Open the notebook in Google Colab
2. Upload `train.csv` when prompted
3. Run all cells sequentially

**Submitted by:**  
Theophilus Mensah (01250686B)  
Date: July 2026
