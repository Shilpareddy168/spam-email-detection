# Spam Email Detection using Machine Learning
## Project Overview

Spam Email Detection is a machine learning project that classifies messages as **Spam** or **Not Spam**.

The project uses Natural Language Processing (NLP) techniques to convert text messages into numerical features and machine learning algorithms to make predictions.

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* NLP
* TF-IDF

## Machine Learning Algorithms

The project uses and compares:

* Naive Bayes
* Logistic Regression
* Support Vector Machine (SVM)

The best-performing model is selected based on the evaluation results.

## Project Workflow

```text
Email / Message
       ↓
Text Preprocessing
       ↓
TF-IDF Vectorization
       ↓
Train-Test Split
       ↓
Machine Learning Models
       ↓
Model Evaluation
       ↓
Spam / Not Spam Prediction
       ↓
Risk Score
```

## NLP Technique

### TF-IDF

TF-IDF (Term Frequency-Inverse Document Frequency) converts text into numerical values that can be understood by machine learning algorithms.

Words that are important in a message receive higher importance compared with very common words.

## Prediction

The system can take a new message and predict whether it is:

* Spam
* Not Spam

For example:

**Input:**

> Congratulations! You won a free iPhone. Click now to claim your prize!

**Prediction:**

> Spam

## Risk Score

The project also provides a risk score to indicate how suspicious a message is.

Example:

```text
Prediction: Spam
Risk Score: 74/100
Risk Level: High
```

The system can also display suspicious words or patterns that contributed to the risk.

## Model Evaluation

The machine learning models are evaluated using metrics such as:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

## Project Structure

```text
spam-email-detection/
│
├── spam_email_detection.ipynb
├── README.md
├── requirements.txt
└── screenshots/
```

## How to Run

1. Open the notebook in Google Colab.
2. Upload or connect the required dataset.
3. Run the cells from top to bottom.
4. Enter a new message for prediction.
5. View the prediction and risk score.

## Future Improvements

* Improve the risk scoring system.
* Add a web interface using Flask or FastAPI.
* Add more spam message datasets.
* Improve explainability of predictions.
* Deploy the application online.

## Author

T. Shilpa Reddy

B.Tech CSE (AI & ML)
