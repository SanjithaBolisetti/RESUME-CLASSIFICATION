# RESUME-CLASSIFICATION

## Resume Classification using TF-IDF and Logistic Regression

This project builds a machine learning pipeline to classify resumes into job categories. It performs text preprocessing, vectorizes the data using TF-IDF, and uses a Logistic Regression model for classification.

---

## Objective

To develop a model that can automatically classify resume texts into predefined job categories using natural language processing (NLP) and machine learning techniques.

---

## Dataset Format

The dataset should be in a CSV format with the following columns:

- **`resume`**: Raw text content of the resume.
- **`category`**: The job title/category label (e.g., "Data Scientist", "HR", "Marketing").

Example:

| resume                                               | category         |
|------------------------------------------------------|------------------|
| "Experienced in Python, SQL and Machine Learning..." | Data Scientist   |
| "Handled recruitment and employee engagement..."     | HR               |

---

## Preprocessing Steps

- Tokenization
- Lowercasing
- Stopword Removal
- Lemmatization (using NLTK)

---

## Model Pipeline

1. Preprocess text using NLTK
2. Convert text to numeric features using **TF-IDF Vectorizer**
3. Split the dataset into training and test sets
4. Train a **Logistic Regression** model
5. Evaluate using **Accuracy** and **Classification Report**

---

## Requirements

Install the required Python libraries:

```
bash
pip install pandas nltk scikit-learn
```
---

##  How to Run

Place your dataset file as resumes.csv in the same directory.

Launch the Jupyter Notebook.

Open and run resume_csv_classifier.ipynb.

---

## Accuracy and Classification report:

<img width="578" height="617" alt="image" src="https://github.com/user-attachments/assets/d8eb9924-5ead-42c9-afc4-846d4fa3eb00" />

---

## Future Improvements

Use more advanced models (e.g., SVM, BERT)

Add resume parsing and keyword extraction

Build a web interface for uploading resumes
