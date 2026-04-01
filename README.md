# IVF Treatment Outcome Prediction

## Overview

This project uses machine learning to predict IVF (In Vitro Fertilisation) success based on patient clinical and demographic data from the HFEA dataset.

## Objective

To develop predictive models that estimate the likelihood of successful IVF outcomes and identify key factors influencing treatment success.

## Dataset

* Source: Human Fertilisation and Embryology Authority (HFEA)
* Includes patient demographics, treatment details, and clinical outcomes

## Methods

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Handling Class Imbalance (RandomUnderSampler)
* Model Training & Evaluation

## Models Used

* Decision Tree Classifier
* Random Forest Classifier
* Support Vector Machine (SVM)

## Evaluation Metrics

* Accuracy
* Precision & Recall
* F1 Score
* ROC-AUC

## Results

* Models achieved approximately 63–68% accuracy
* Decision Tree showed strong performance in predicting IVF outcomes
* Key predictive features included patient age, infertility cause, and treatment type

## Key Insights

* Patient age is a major factor in IVF success
* Treatment type and infertility cause significantly influence outcomes
* Machine learning can support clinical decision-making in reproductive health

## Tools & Technologies

* Python (Pandas, NumPy, Scikit-learn)
* Matplotlib & Seaborn
* Jupyter Notebook

## Project Structure

* ivf_model.ipynb → main analysis and modelling
* visuals/ → charts and outputs
* ## 📂 Project Files

- 📄 [Project Summary](ivf_project_summary.pdf)
- 📊 [Notebook](ivf_model.ipynb)
