# Urdu News Classification 📄🇵🇰

A machine learning pipeline built to classify Urdu-language news articles collected from various Pakistani news sources. This project involved web scraping over 1400 articles, preprocessing and cleaning Urdu text data, and implementing multiple classification models to determine the most accurate approach for categorizing the news content.

---

## 🧠 Models Implemented

- **Multinomial Naive Bayes (MNB)**
- **Logistic Regression**
- **Artificial Neural Network (ANN)**

After evaluating the accuracy of all three, **Multinomial Naive Bayes** was selected as the best-performing classifier for this specific dataset.

---

## 🗃 Dataset

- ~1400 Urdu articles
- Scraped from 5 different Pakistani news outlets
- Preprocessed for:
  - Removal of HTML tags
  - Tokenization
  - Stopword removal
  - Shuffling for training consistency

---

## ⚙️ Tech Stack

- **Python**
- **BeautifulSoup4** & **Requests** – Web scraping
- **scikit-learn** – ML model development and evaluation
- **TensorFlow/Keras** – ANN implementation
- **Pandas**, **NumPy** – Data wrangling
- **Matplotlib**, **Seaborn** – Visualizations

---

## 📊 Results

| Model                  | Accuracy  |
|------------------------|-----------|
| Multinomial Naive Bayes | ✅ Best |
| Logistic Regression    | Medium    |
| Artificial Neural Network | Moderate |

---

# ✍️ About

This project was developed with the goal of applying machine learning to low-resource languages like Urdu. The motivation stems from a personal and academic interest in Natural Language Processing (NLP), particularly for underrepresented languages and regions. By focusing on Urdu news data, this project explores how standard NLP pipelines can be adapted to a language with different script, structure, and linguistic patterns compared to English.

---

## 🚀 Future Work

- Improve preprocessing using NLP libraries like `urduhack`
- Explore deep learning models (e.g., BERT-based for Urdu)
- Deploy as a Flask/Streamlit app for live classification

---

## 🧑‍💻 Author

Ahmed Hassan – [@tk1475](https://github.com/tk1475)
