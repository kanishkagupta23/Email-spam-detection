# 📧 SMS/Email Spam Detection Web App

A real-time web application that classifies messages as **Spam** or **Not Spam** using a machine learning model. Built with Python, Scikit-learn, and Streamlit, this project demonstrates how textual data can be processed and analyzed for spam detection.

## 🔍 Features
- Accepts user-input messages
- Transforms and analyzes text data
- Predicts using a trained ML model
- Simple, interactive UI with Streamlit

## 🚀 Tech Stack
- **Frontend**: Streamlit  
- **Backend**: Python  
- **Libraries**: Scikit-learn, NLTK, Pickle  
- **Model**: TF-IDF + Classification Algorithm (e.g., Naive Bayes)

## 🛠️ How to Run Locally
1. Clone the repository  
   ```bash
   git clone https://github.com/kanishkagupta23/spam-detector-app.git
   cd spam-detector-app
2.pip install -r requirements.txt

3.import nltk
nltk.download('punkt')
nltk.download('stopwords')

4.streamlit run app.py
