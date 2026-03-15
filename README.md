Movie Recommendation System
A content-based movie recommender system built with Python that suggests similar movies based on your selection, complete with movie posters fetched from TMDB API.

Features
- Select any movie from 5000+ titles
- Get 5 similar movie recommendations instantly
- Movie posters fetched live from TMDB API

Tech Stack
- Python
- Streamlit
- Scikit-learn (cosine similarity)
- Pandas & NumPy
- TMDB API
- Pickle

Dataset
TMDB 5000 Movie dataset from kaggle

How It Works
- Movies are vectorized using tags (genres, keywords, cast, crew, overview)
- Cosine similarity is computed between all movie vectors
- Top 5 most similar movies are returned on selection

