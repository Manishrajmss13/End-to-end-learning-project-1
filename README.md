# Student Performance Predictor

A machine learning web application to predict student academic performance based on demographic and previous scores. This project demonstrates end-to-end ML workflow: data ingestion, preprocessing, model training, evaluation, and deployment.

---

## Project Overview

- **Goal:** Predict student scores (reading & writing) based on:
  - Gender
  - Race/Ethnicity
  - Parental education
  - Lunch type
  - Test preparation course
  - Math scores
- **Approach:** Multiple regression models (Random Forest, Gradient Boosting, Linear Regression, XGBoost, CatBoost, AdaBoost, Decision Tree) were trained and evaluated using R² scores to select the best model.
- **Data Handling:** Used `pandas` and `numpy` for preprocessing, categorical encoding, and scaling.
- **Model Saving:** Models serialized using `dill`/`pickle` for deployment.
- **Web Interface:** Flask app with a simple UI where users input student data and get predictions.

---

## Key Features

- **End-to-End ML Pipeline:** From CSV ingestion → preprocessing → training → prediction.
- **Multiple Models:** Automatic selection of the best-performing model.
- **Reusable Components:** Separate modules for data ingestion, transformation, training, and prediction.
- **Deployment Ready:** Ready to deploy on free hosting platforms like Render.

---

## Deployment

- **Deployed URL:** [Student Performance Predictor](https://student-performance-predictor-s9ky.onrender.com)
- **Technology:** Flask, Gunicorn
- **Usage:** Enter student details and click **Predict** to get predicted scores.

---

## Screenshots sample

<img width="1354" height="604" alt="project1a1" src="https://github.com/user-attachments/assets/3aed763b-bef2-4dd3-8873-d5bbda65f9fc" />
<img width="1353" height="624" alt="project1a" src="https://github.com/user-attachments/assets/dde60c31-00bb-4ec7-9581-fd03ac6ad583" />

---

## Author

**Manish Raj**  
[GitHub Profile](https://github.com/Manishrajmss13)
