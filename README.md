# Student Performance Predictor

## Overview
This is a machine learning project that predicts whether a student will Pass or Fail based on key academic factors such as study hours, attendance percentage, and previous exam score.

This project was developed as part of an AI/ML course to demonstrate the practical application of machine learning.

---

## What This Project Does

- Generates a dataset of 300 students with relevant academic information  
- Performs data analysis and visualization  
- Creates charts to understand:
  - Pass vs Fail distribution  
  - Study hours distribution  
  - Correlation between features  
- Trains and compares three machine learning models:
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  
- Selects the best-performing model based on accuracy  
- Saves the trained model for future use  
- Provides an interactive system for predicting student performance  

---

## Project Workflow

1. Generate dataset  
2. Perform data visualization  
3. Train machine learning models  
4. Compare model performance  
5. Select the best model  
6. Save the trained model  
7. Take user input and predict result  

---

## How to Run the Project

### Step 1: Install Dependencies

```bash
pip install -r requirements.txt

Step 2: Run the Project
python main.py

Project Structure
project-folder/
│── main.py
│── requirements.txt
│── students.csv
│── charts/
│── model/

Example Output
[Step 4] Training and comparing models...

Model                   Accuracy   CV Score
--------------------------------------------
Logistic Regression       86.67%     85.21%
Decision Tree             88.33%     87.10%
Random Forest             91.67%     90.43%

The best model is Random Forest.
The accuracy of the model is 91.67%.

Interactive Predictor
Enter study hours per day (1–9): 6
Enter attendance percentage (40–100): 85
Enter previous score (0–100): 72


Output
Result: PASS
Confidence: Pass = 88.0% | Fail = 12.0%


Technologies Used
Python 3
pandas
numpy
scikit-learn
matplotlib
seaborn


Key Features
Simple and easy-to-understand implementation
Multiple model comparison
Automatic dataset generation
Data visualization support
Model saving for reuse
Interactive prediction system


Conclusion
This project demonstrates how machine learning can be used to analyze student data and predict academic performance.
It provides practical experience in data processing, model training, evaluation, and prediction.

Author
Pratyush Prasad
