# 📰 Fake News Detection using NLP and Machine Learning

This project focuses on building a binary text classification model to detect fake news articles based on their titles using Natural Language Processing and Machine Learning techniques.

---

## 📌 Project Features

- Cleaned and preprocessed real-world fake news data from Kaggle
- Applied text normalization techniques: tokenization, stopword removal, and stemming
- Created Bag-of-Words features using **CountVectorizer** with uni-, bi-, and tri-grams
- Built models using:
  - 🔹 **Multinomial Naive Bayes**
  - 🔹 **Logistic Regression**
- Performed **hyperparameter tuning** to optimize accuracy
- Evaluated model performance using:
  - Accuracy, Precision, Recall
  - Confusion Matrix with visualization
- Designed a function to classify new/unseen news as **Fake** or **Real**

---

## 🔧 Tech Stack

- **Language**: Python  
- **Libraries**: `NLTK`, `scikit-learn`, `pandas`, `matplotlib`, `seaborn`  
- **Dataset**: [Kaggle Fake News Dataset](https://www.kaggle.com/datasets)

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/fake-news-detector.git
   cd fake-news-detector
