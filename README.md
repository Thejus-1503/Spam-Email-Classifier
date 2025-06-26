# Spam-Email-Classifier
# 📧 Spam Email Classifier

This project is part of my 1-month Artificial Intelligence Internship. The goal is to build a machine learning model that can classify emails as **spam** or **not spam** using Natural Language Processing (NLP) techniques.

## 🧠 Project Objective

To develop a text classification model that identifies spam messages based on their content. This helps in automatically filtering unwanted emails and improving email security.

---

## 📂 Dataset

- **Source**: []
---

## 🛠️ Tools & Technologies

- Python
- Pandas
- Scikit-learn
- NLTK (for basic preprocessing)
- CountVectorizer
- Naive Bayes Classifier

---

## 🚀 Steps Involved

1. **Data Loading & Cleaning**
   - Loaded dataset using `pandas`.
   - Cleaned unnecessary columns and encoded labels.

2. **Text Vectorization**
   - Converted text to numerical features using `CountVectorizer`.

3. **Model Training**
   - Used a **Multinomial Naive Bayes** classifier.
   - Evaluated performance using accuracy score.

4. **Testing**
   - Tested the model on new sample messages to classify as spam or ham.

---

## 📊 Model Performance

- **Accuracy**: ~98% on test data
- Works well for binary spam classification on short messages.
