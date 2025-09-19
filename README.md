## APR-Assignment
# Wine Quality Prediction & Analysis  
Pattern Recognition Assignment – Comparative Study of Classification & Regression Models with Visualizations  

---

## Author  
**Ramendra Bharadwaj**  
IIT Patna – Pattern Recognition Assignment  

---

## Project Overview  
This project focuses on the **Wine Quality dataset (Red & White wines)** and performs a comparative study of multiple machine learning models for both **classification** and **regression** tasks. Along with predictive modeling, the project also includes **Exploratory Data Analysis (EDA)** and **dimensionality reduction with PCA** for visualization.  

The assignment demonstrates how different algorithms perform for:  
- **Classification**: Predicting wine quality as *high* (≥6) vs *low* (<6)  
- **Regression**: Predicting the exact numerical *wine quality score*  

---

## Dataset  
Two datasets were used, both from the **UCI Machine Learning Repository**:  
- `winequality-red.csv`  
- `winequality-white.csv`  

Both datasets were combined into a single dataframe with an additional column:  
- `wine_type`: Red or White  

---

## Models Used  

### Classification  
- Logistic Regression  
- Support Vector Classifier (SVC)  
- K-Nearest Neighbors (KNN)  

### Regression  
- Linear Regression  
- Support Vector Regressor (SVR)  

### Dimensionality Reduction  
- Principal Component Analysis (PCA)  

---

## Exploratory Data Analysis (EDA)  
Some of the visualizations included:  
- Distribution of wine quality for Red vs White wines  
- Correlation heatmap of chemical properties  
- Boxplots and density plots for alcohol content vs wine quality  
- Pair plots for selected chemical features  
- PCA projection for dimensionality reduction  

---

## Evaluation Metrics  

### Classification  
- Accuracy Score  
- Classification Report (Precision, Recall, F1-score)  
- Confusion Matrix  

### Regression  
- Mean Squared Error (MSE)  
- R² Score (Coefficient of Determination)  

---

## Results  

- **Classification**:  
  Logistic Regression, SVM, and KNN showed competitive performance, with results summarized using confusion matrices and accuracy scores.  

- **Regression**:  
  - Linear Regression gave interpretable results but with limitations on model fit.  
  - SVR performed better in capturing non-linear relationships.  

- **PCA**:  
  PCA revealed that alcohol, sulphates, and citric acid have significant roles in distinguishing red vs white wines in 2D projections.  

- **Feature Importance** (Logistic Regression):  
  Logistic regression coefficients indicated which chemical properties most influence wine quality classification.  

---

## Visualizations  

Key visualizations included in the notebooks:  
- Quality distribution plots (Red vs White)  
- Heatmap of correlations  
- PCA scatter plots  
- Predicted vs Actual regression plots  
- Confusion matrices per classifier  
- Logistic regression feature importance chart  

---

## Tech Stack  

- **Programming Language**: Python  
- **Libraries**:  
  - Data Handling: `numpy`, `pandas`  
  - Visualization: `matplotlib`, `seaborn`  
  - ML Models: `scikit-learn`  
  - Metrics: `accuracy_score`, `classification_report`, `mean_squared_error`, `r2_score`  

---

