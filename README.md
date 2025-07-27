# 🍷 Wine Quality Prediction

This project explores how we can use machine learning to predict the quality of red wine based on various chemical properties. The idea is simple: given information like acidity, alcohol content, and sugar levels, can we guess how good a wine is?

I used a dataset from the UCI Machine Learning Repository and experimented with different regression models to see which one performs best.

---

## About the Project

Wine quality is rated on a scale from 0 to 10. Instead of classifying the wine (like good vs bad), I approached this as a regression problem — predicting a numerical quality score.

---

## 🛠 Tools & Libraries

- Python (Jupyter Notebook)
- Scikit-learn
- Pandas
- NumPy
- Matplotlib / Seaborn

---

## 🧪 Models Tried

- Linear Regression  
- Polynomial Regression  
- Random Forest Regressor

I started simple with linear regression, moved on to polynomial regression, and finally used Random Forest to improve performance. The Random Forest model gave the best results.

---

## 📊 Results

| Model                   | R² Score |
|------------------------|----------|
| Linear Regression       | 0.44     |
| Polynomial Regression   | ~0.44    |
| Random Forest Regressor | **0.46** |

Even though the R² scores aren’t super high, they’re decent considering the small and somewhat noisy dataset.

---

## 📈 Process Overview

 **Data Exploration**  
   - Checked for null values  
   - Looked at distributions and correlations between features  
   - Explored how each chemical property affects wine quality

 **Preprocessing**  
   - Normalized features  
   - Split data into training and test sets

 **Modeling**  
   - Built and trained multiple models  
   - Tuned Random Forest parameters manually  
   - Compared model performance using R² score

 **Evaluation**  
   - Plotted prediction results  
   - Visualized feature importance (in Random Forest)

---




