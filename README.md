
### 📄 README.md
```markdown
# 🧠 IT Ticket Classifier with LLM & NLTK

This project classifies IT support tickets into categories like "network", "software", and "hardware" using a simple NLP pipeline with NLTK and a Logistic Regression classifier. The predictions are logged in a PostgreSQL database.

## 🚀 Features
- Preprocess ticket text with NLTK
- Classify tickets using TF-IDF + Logistic Regression
- Store predictions in PostgreSQL

## 📦 Tech Stack
- Python, NLTK, Scikit-learn, PostgreSQL, psycopg2

## 🛠️ Setup Instructions
```bash
pip install -r requirements.txt
python src/train_model.py
python src/predict.py
```

## 🗃️ PostgreSQL Setup
```bash
psql -U postgres -f db/init.sql
```

## 🧪 Sample Prediction
```bash
python src/predict.py
# Output: Predicted Category: software
```

## 📝 Author
Built to demonstrate ITES/ITOrk + NLP/LLM + DB integration.
```