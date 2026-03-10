# Accident Severity Prediction 🚗

## Project Overview
Built a Random Forest Classifier model to predict accident severity 
(Injured/Killed/Unknown) using NYC Motor Vehicle Collision dataset.

## Dataset
- Total Records: 230,660
- Total Features: 21
- Source: NYC Motor Vehicle Collisions (Police Reported)
- Target Variable: PERSON_INJURY

## Model Results
- ✅ Accuracy: 99.64%
- ✅ Model: Random Forest Classifier
- ✅ Top Feature: EMOTIONAL_STATUS (80.6% importance)
- ✅ Compared with Logistic Regression (99.53%)

## Feature Importance
| Feature | Importance |
|---------|-----------|
| EMOTIONAL_STATUS | 80.6% |
| COMPLAINT | 8.5% |
| BODILY_INJURY | 3.8% |
| PED_ACTION | 1.7% |
| PERSON_TYPE | 1.7% |

## Tools & Technologies
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Random Forest Classifier
- Logistic Regression

## Project Steps
1. Data Loading & Exploration
2. Missing Value Treatment
3. Exploratory Data Analysis (EDA)
4. Label Encoding
5. Train Test Split (80/20)
6. Model Building
7. Model Evaluation
8. Feature Importance Analysis

## Business Impact
- Supports emergency response planning
- Helps prioritize resources for severe accidents
- Identifies key risk factors for road safety

## Author
**Akanksha Dubey**
Data Science & AI | First Quadrant Labs | 2026
