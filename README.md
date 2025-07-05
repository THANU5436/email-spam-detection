# Email Spam Detection Project

This project is a simple machine learning pipeline for detecting spam emails using Python, scikit-learn, and natural language processing (NLP) techniques.

---

## Features

- Loads and processes an email dataset (CSV format)
- Cleans and vectorizes email text (using NLTK, TfidfVectorizer)
- Trains a machine learning model (e.g., Naive Bayes, Logistic Regression)
- Evaluates the model (classification report, confusion matrix)
- Handles common issues such as imbalanced data and precision warnings

---

## Requirements

- Python 3.x
- scikit-learn
- pandas
- numpy
- nltk

Install dependencies:
```sh
pip install scikit-learn pandas numpy nltk
```

---

## Getting Started

1. **Clone or Download the Repository**
2. **Prepare the Dataset**
   - Place your email dataset CSV file in the project directory.
   - Each row should have at least two columns: one for the email/message and one for the label (spam/ham).

3. **Run the Script**
   ```sh
   python email_spam_detection.py
   ```

4. **View Results**
   - The script will print out performance metrics such as accuracy, classification report, and confusion matrix.

---

## Handling Warnings

If you see a warning like:
```
UndefinedMetricWarning: Precision is ill-defined and being set to 0.0 due to no predicted samples.
```
This is usually caused by:
- Model not predicting any samples for a certain class
- Imbalanced dataset

**See [SPAM_MODEL_WARNING_GUIDE.md](SPAM_MODEL_WARNING_GUIDE.md) for details and solutions.**

---

## Next Steps

- Try different classifiers (Logistic Regression, Random Forest, etc.)
- Use a larger or more balanced dataset
- Build a simple web interface (Streamlit, Flask)
- Save and reload your model with joblib
- Experiment with advanced NLP features

---

## License

This project is for educational purposes. Feel free to use and modify it for your own learning.

---

## Author

THANU5436
