# Detection of heart disease using a linear model

[![Python 3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

A machine learning project for predicting heart disease using linear models.

## 📋 About the project

This project uses machine learning methods to classify patients based on the presence or absence of heart disease. The project is based on linear models such as logistic regression.  
[**Link to the dataset from Keggel**](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)

## 🚀 Quick start

### Preliminary requirements

- Python 3.8 or higher
- pip (Python package manager)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/heart-disease-detection.git
cd heart-disease-detection
```

## **View my solution**

- [View IPython Notebook](https://github.com/yarmukh/Heart-Failure-Prediction/blob/main/notebook.ipynb)

## 📊 **About dataset**

### Context of the problem
Cardiovascular diseases are the leading cause of death worldwide, claiming about **19.8 million lives each year** (\~32% of all deaths). **Eighty-five percent** of these cases are caused by **heart attacks and strokes**, with **one-third occurring in people under 70**. **Heart failure**, affecting more than **64 million people**, is a common consequence of these conditions. Among the key risk factors is **hypertension**, which affects around **26% of adults** and precedes heart failure in **90% of cases**. Chronic diseases, including cardiovascular ones, account for **75% of all deaths**, and cardiovascular diseases remain a “silent killer,” taking **one in three lives** globally.


### **Dataset Description**

**Dataset size:** 918 observations

**Data sources:**
The dataset was created by merging 5 different datasets:

 - Cleveland: 303 observations

 - Hungarian: 294 observations

 - Switzerland: 123 observations

 - Long Beach VA: 200 observations
 
 - Stalog (Heart) Data Set: 270 observations

**Total initial volume:** 1190 observations
**Duplicates removed:** 272 observations
**Final volume:** 918 observations

### Data Attributes

| Feature            | Description                                                                                                                                                                                             | Data Type        |
| ------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------- |
| **Age**            | Age of the patient                                                                                                                                                                                      | years            |
| **Sex**            | Sex of the patient \[M: Male, F: Female]                                                                                                                                                                | categorical      |
| **ChestPainType**  | Chest pain type \[TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]                                                                                                   | categorical      |
| **RestingBP**      | Resting blood pressure                                                                                                                                                                                  | mm Hg            |
| **Cholesterol**    | Serum cholesterol                                                                                                                                                                                       | mg/dl            |
| **FastingBS**      | Fasting blood sugar \[1: if FastingBS > 120 mg/dl, 0: otherwise]                                                                                                                                        | binary           |
| **RestingECG**     | Resting electrocardiogram results \[Normal: Normal, ST: ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: left ventricular hypertrophy by Estes' criteria] | categorical      |
| **MaxHR**          | Maximum heart rate achieved                                                                                                                                                                             | numeric (60–202) |
| **ExerciseAngina** | Exercise-induced angina \[Y: Yes, N: No]                                                                                                                                                                | binary           |
| **Oldpeak**        | Oldpeak = ST (value measured in depression)                                                                                                                                                             | numeric          |
| **ST\_Slope**      | Slope of the peak exercise ST segment \[Up: upsloping, Flat: flat, Down: downsloping]                                                                                                                   | categorical      |
| **HeartDisease**   | Output class \[1: heart disease, 0: Normal]                                                                                                                                                             | binary           |


###**Source**

[Data obtained from the UCI Machine Learning Repository:](https://archive.ics.uci.edu/ml/machine-learning-databases/heart-disease/)

###**Dataset creators:**

- Hungarian Institute of Cardiology, Budapest: Dr. Andras Janosi

- University Hospital Zurich, Switzerland: Dr. William Steinbrunn

- University Hospital Basel, Switzerland: Dr. Matthias Pfisterer

- V.A. Medical Center, Long Beach and Cleveland Clinic Foundation: Dr. Robert Detrano

Data donor: David W. Aha (University of California, Irvine)
