# Smoking Classification Using Vital Health Signs

This project aims to identify smokers based on non-invasive biological health signals using a machine learning classification model. By analyzing key vital signs, the model provides an objective method to assess smoking status, reducing reliance on self-reported data.

---

## Project Type

- Binary Classification  
- Unguided Machine Learning Project

---

## Objective

To build a machine learning model that predicts whether an individual is a smoker or non-smoker using basic health indicators such as blood pressure, cholesterol levels, and other non-invasive metrics.

---

## About the Dataset

The dataset contains vital health data collected from over 55,000 individuals. It includes information such as age, blood pressure, blood sugar, cholesterol, and hearing/vision status.


### Key Features

- Age, Gender, Height, Weight  
- Blood pressure (systolic and diastolic)  
- Cholesterol (Total, HDL, LDL)  
- Blood sugar, hemoglobin, liver enzymes (AST, ALT, GTP)  
- Oral and dental health status  
- Vision and hearing scores

---

## Approach

- Preprocessed the data to handle missing values and normalize input features  
- Used `RandomForestClassifier` as the primary model  
- Applied `GridSearchCV` for hyperparameter tuning to optimize model performance  
- Split the data into training and validation sets for robust evaluation

---

## Results

- Final model achieved **94% accuracy** on the test set  
- Precision for non-smokers: **0.95**  
- Precision for smokers: **0.91**  
- Demonstrated strong performance in identifying both classes, especially useful in public health settings where objective indicators are preferred

---

## Tools and Libraries

- Python (Pandas, NumPy)  
- Scikit-learn (RandomForest, GridSearchCV)  
- Matplotlib / Seaborn for visualization

---

