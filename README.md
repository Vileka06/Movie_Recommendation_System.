# 🎬 Movie Recommendation System

A **hybrid movie recommendation application** built with Python and Streamlit. The system combines content-based and collaborative filtering to generate personalized movie suggestions from movie metadata and user ratings.

## ✨ Features

- 🎭 Content-based recommendations using movie genres
- 👥 Collaborative filtering using user-rating patterns
- 🔀 Hybrid recommendation approach
- 🧠 TF-IDF vectorization and cosine similarity
- 📊 Data preprocessing with Pandas
- 🖥️ Interactive Streamlit interface
- 🎯 Top movie recommendations for a selected title

## 🛠️ Tech Stack

**Language:** Python  
**Framework:** Streamlit  
**Data:** Pandas  
**Machine Learning:** Scikit-learn, TF-IDF, cosine similarity  
**Dataset:** MovieLens / Kaggle movie and rating data

## 🏗️ Recommendation Pipeline

```text
Movies + Ratings
       ↓
Data Cleaning & Preprocessing
       ↓
 ┌───────────────┬──────────────────┐
 ↓               ↓                  ↓
Content-Based  Collaborative    User Preference
 ↓               ↓                  ↓
 └───────────────┴──────────────────┘
                 ↓
          Hybrid Recommendation
                 ↓
          Top Movie Suggestions
```

## 🚀 Getting Started

```bash
git clone https://github.com/Vileka06/Movie_Recommendation_System..git
cd Movie_Recommendation_System.
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python -m streamlit run movieapp.py --server.port 8502
```

Open `http://localhost:8502` in your browser.

## 🧠 How It Works

### Content-Based Filtering

Movie genres are transformed into TF-IDF vectors. Cosine similarity is then used to identify movies with similar genre profiles.

### Collaborative Filtering

A user-movie rating matrix is used to identify patterns in user preferences and generate recommendations based on similar tastes.

### Hybrid Model

The application combines signals from both approaches to produce the final recommendation list.

## 📊 Example

Select a movie and the application returns a list of recommended titles based on the available movie metadata and rating patterns.

## 📚 Key Learning Outcomes

- Building recommendation-system pipelines
- Working with real-world datasets
- Feature extraction using TF-IDF
- Measuring similarity with cosine distance
- Combining multiple recommendation strategies
- Building an interactive ML application with Streamlit

## 📌 Future Improvements

- Add richer movie metadata such as cast, director and keywords
- Improve collaborative filtering with matrix factorization
- Add movie posters and external metadata
- Deploy the application for public use

**Built with Python, Pandas, Scikit-learn and Streamlit.**