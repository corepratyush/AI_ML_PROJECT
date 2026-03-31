#  Simple Sentiment Analysis Using Python & Machine Learning

##  Overview
This project is a beginner-friendly AI/ML-based **Sentiment Analyzer** that predicts whether a given sentence expresses a **positive** or **negative** sentiment.

It uses a small custom dataset for training and applies basic Natural Language Processing (NLP) techniques. The model is trained using the **Naive Bayes classifier**, a simple and fast algorithm suitable for text classification.

The user can enter any sentence at runtime, and the system instantly returns:
- Predicted sentiment
- Confidence score

---

##  Features
-  Classifies text into **Positive** or **Negative** sentiment  
-  Real-time prediction based on user input  
-  Uses **Bag-of-Words** model for text processing  
-  Lightweight and easy to understand  
-  Ideal for beginner AI/ML projects  
-  No large datasets required  

---

##  Technologies / Tools Used
- **Python 3**
- **scikit-learn** (Machine Learning)
- **CountVectorizer** (NLP – Bag of Words)
- **Naive Bayes Classifier**
- **NumPy**

---

##  How the System Works
1. A small dataset of positive and negative sentences is defined manually  
2. **CountVectorizer** converts text into numerical features (Bag-of-Words)  
3. A **Naive Bayes classifier** is trained on this dataset  
4. User enters a sentence during runtime  
5. The model predicts the sentiment and displays:
   - Sentiment label (**Positive/Negative**)
   - Confidence score  

---

##  Steps to Install & Run the Project

### 1. Install Python
Make sure **Python 3.x** is installed on your system.

### 2. Install Required Libraries
Open terminal / CMD and run:
```bash
pip install scikit-learn
pip install numpy
