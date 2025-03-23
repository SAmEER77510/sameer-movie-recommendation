# 🎬 Movie Recommendation System

This project is a **Content-Based Movie Recommendation System** built using **Python, NLP, and Django**. It recommends movies similar to the one a user selects, based on genres, keywords, cast, and crew from the TMDB dataset.

---

## 🚀 Project Overview

Users can enter the name of a movie, and the system will return the **top 5 most similar movies** using NLP-based similarity scores. The web interface is powered by **Django**, making it easy to interact with the model through a browser.

---

## 📁 What's Included

- `Movie_Recommended_System.ipynb` – Jupyter Notebook containing model logic, preprocessing, vectorization, and similarity matrix creation  
- `movie_recommendation/` – Django web application with integrated recommendation backend  
- `similarity.pkl` – Precomputed similarity matrix for fast predictions  
- `tmdb_5000_movies.csv` & `tmdb_5000_credits.csv` – TMDB datasets used for model training  
- `env/` – Virtual environment for project dependencies *(optional to include in GitHub)*  
- `movie_recommendation_demo.mp4` – Video walkthrough of the working web application  

---

## 🔍 Features

- Clean NLP pipeline using:
  - Tokenization
  - Stemming
  - CountVectorizer
- Cosine similarity to recommend relevant movies
- Django-based web interface with input form
- Error handling for movie name not found
- Fast predictions using precomputed `.pkl` file

---

## 📦 Libraries & Tools

- Python, Pandas, Numpy
- Scikit-learn (CountVectorizer, Cosine Similarity)
- NLTK (PorterStemmer)
- Django (for web deployment)
- Jupyter Notebook

---

## 💻 How to Run Locally

```bash
# 1. Clone the repo
git clone https://github.com/yourusername/movie-recommender

# 2. Navigate into project
cd movie-recommendation

# 3. Activate virtual environment
source env/Scripts/activate  # or use 'env\Scripts\activate.bat' on Windows

# 4. Run Django server
python manage.py runserver

# 5. Open in browser
http://127.0.0.1:8000/

---

## 📬 Contact


👤 Sameer – Machine Learning Engineer
📧 sameergadit321@gmail.com
Phone: +92 330 8731160

🌐 LinkedIn {www.linkedin.com/in/sameer-gadit-761322318}

