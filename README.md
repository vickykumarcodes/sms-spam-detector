# 📩 SMS/Email Spam Classifier

A machine learning project that classifies messages as **Spam** or **Not Spam** using Natural Language Processing and the **Multinomial Naive Bayes** algorithm. Deployed with **Streamlit** for easy user interaction.

---

## 🚀 Features

- Cleaned and preprocessed text data
- TF-IDF Vectorization
- Trained on the [SMS Spam Collection Dataset](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- Model accuracy: ~98%
- Interactive Web App using Streamlit
- Real-time spam prediction

---

## 🧠 How It Works

1. User enters a message.
2. Text is cleaned, tokenized, and stemmed.
3. Transformed using a trained TF-IDF vectorizer.
4. Classified by the trained Naive Bayes model.
5. Output displayed as **Spam** or **Not Spam**.

---

## 💻 Run the App Locally

```bash
git clone https://github.com/VickyKumar2508/spam-classifier.git
cd spam-classifier
pip install -r requirements.txt
streamlit run app.py
