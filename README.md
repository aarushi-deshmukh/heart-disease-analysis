# Heart Disease Prediction and Exploratory Data Analysis

This project involves exploratory data analysis (EDA) and machine learning-based prediction to determine the likelihood of heart disease based on clinical data. The goal is to uncover patterns in the dataset and build models that can aid in early detection and risk stratification, which is crucial for timely treatment.

---

## Key Highlights

- In-depth EDA covering feature distributions, relationships, and class imbalance.

- Implementation of multiple classification models:
  - Logistic Regression
  - Support Vector Machine (SVM)
  - K Nearest Neighbors (KNN)
  - Decision Tree
  - Random Forest Classifier

- Performance evaluation using:
  - Confusion Matrix
  - ROC Curve and AUC Score

- Visualization of model outputs side-by-side for comparison.

---

## Visualizations

The project includes several insightful plots:
- **Bar Charts** for distribution of target variable by chest pain type, ECG results, exercise-induced angina
- **Histograms & Count Plots** of features like cholesterol, blood pressure, and age.
- **Box and Violin Plots** for visualization of outliers and spread in features like resting blood pressure and oldpeak
- **Correlation Heatmap** to identify strongly related features.
- **Confusion Matrices** for all models with intuitive labels.
- **ROC Curves plotted** with corresponding AUC scores for model comparison.

---

## Files

- `heart-diseaseEDA.ipynb` – Exploratory data analysis and visualization  
- `heart.csv` – Original dataset used  
- `Heart_Disease_Dashboard.twb` – Tableau workbook  
- `heart-disease-prediction.ipynb` – Model building, training, evaluation, and ROC plots.

---

## Tools Used

- **Python**  
  - `Pandas`, `NumPy` – Data analysis and handling 
  - `Matplotlib`, `Seaborn` – for Plotting and Visualization  
  - `scikit-learn` – for machine learning models and evaluation
- **Jupyter Notebook and Google Colab**  
- **Tableau** – Interactive dashboard  
- **Git & GitHub** – Version control and collaboration

---

## Conclusion

The analysis and predictive modeling show that machine learning algorithms, particularly Random Forest, are effective in classifying heart disease presence based on clinical data. The insights gained from EDA and the predictive results can help guide further research or development of diagnostic tools. This project demonstrates how data science can contribute to healthcare by enhancing decision-making with data-driven insights.

