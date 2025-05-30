# 📚 Book Recommendation System

This is a web-based Book Recommendation System built using **Flask** and deployed via **Render**. It recommends books based on user input using collaborative filtering.

---

## 🚀 Features

- 📖 Recommends top books based on similarity
- 🔍 Search by book title
- ✨ Beautiful responsive UI with Bootstrap
- 📬 Contact form for user feedback
- 🧠 Pickle files pre-trained with book data and similarity scores

---

## 📦 Project Structure

book-recommender-system/
│
├── app.py # Main Flask application
├── requirements.txt # All Python dependencies
├── Procfile # For Render deployment
├── books.pkl # Book details
├── popular.pkl # Popular books
├── pt.pkl # Pivot table
├── similarity_score.pkl # Pre-computed similarity matrix
│
├── templates/ # HTML pages
│ ├── index.html
│ ├── recommend.html
│ └── contact.html
│
└── model/ # (optional placeholder for future model training scripts)
