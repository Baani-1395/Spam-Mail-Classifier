# 📧 Spam Mail Classifier

## Overview

The Spam Mail Classifier is a Machine Learning and Natural Language Processing (NLP) project that classifies email or SMS messages as **Spam** or **Ham (Not Spam)**.
The model uses the **TF-IDF Vectorizer** to convert text into numerical features and a **Logistic Regression** algorithm to perform the classification. A simple **Flask web application** allows users to enter a message and instantly check whether it is spam.

---

## Project Objective

The objective of this project is to automatically identify spam messages using machine learning techniques. This helps filter unwanted emails and improves communication by detecting suspicious messages.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Natural Language Processing (NLP)
- TF-IDF Vectorizer
- Logistic Regression
- Flask
- HTML
- CSS
- Jupyter Notebook

---

## Dataset

**Dataset:** Email Spam Collection Dataset

**Columns**
- Category (Spam/Ham)
- Message

**Dataset Size**
- 5572 Messages
- 2 Columns

---

## Machine Learning Workflow

1. Load the dataset.
2. Handle missing values.
3. Encode labels (Spam = 0, Ham = 1).
4. Split the dataset into training and testing sets.
5. Convert text into numerical vectors using TF-IDF.
6. Train the Logistic Regression model.
7. Evaluate the model using accuracy score.
8. Predict whether a new message is Spam or Ham.

---

## Model Performance

- **Training Accuracy:** **97.94%**
- **Testing Accuracy:** **98.36%**

The model achieves high accuracy on both the training and testing datasets, indicating strong performance in classifying spam and ham messages while maintaining good generalization on unseen data.

---

## Features

- Spam and Ham classification
- NLP-based text processing
- TF-IDF feature extraction
- Logistic Regression classifier
- User-friendly Flask web interface
- Predict custom messages

---

## Project Structure

```
Spam-Mail-Classifier/
│── app.py
│── spam_mail_classifier.ipynb
│── mail_data.csv
│── README.md
│── requirements.txt
│
├── templates/
│   └── index.html
│
├── static/
│   └── style.css
│
└── screenshots/
    ├── home.png
    ├── spam_prediction.png
    └── ham_prediction.png
```

## Future Improvements

- Deploy the application online
- Improve accuracy using advanced NLP techniques
- Try additional machine learning algorithms
- Add support for multiple languages

---

## Author

**Bhawani Singh**

