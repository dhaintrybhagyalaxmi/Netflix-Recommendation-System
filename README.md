**Netflix Recommendation System**

**Project Overview**
This project is a movie recommendation system built using Python. It recommends movies to users based on a selected movie by analyzing similarity metrics from TMDB datasets.
The system demonstrates Python programming, data handling, and recommendation logic, making it a strong mini/capstone-level project for SDE portfolios.

**Features**
Search for a movie by title
Recommend top N similar movies
Display movie metadata (genres, release year, rating)
Works with CSV datasets from TMDB

**Tech Stack**
Language: Python
Libraries: pandas, numpy, scikit-learn,streamlit
Dataset: TMDB CSV datasets
IDE: VS Code / Jupyter Notebook

**How to Run**

1.Clone the repository:
git clone https://github.com/dhaintrybhagyalaxmi/NetflixRecommendationSystem.git

2.Navigate to the folder:
cd NetflixRecommendationSystem

3.Install dependencies (if Python):
pip install -r requirements.txt

4.Open the Jupyter notebook netflix_movie_recommendation.ipynb and run all cells
OR run streamlit run app.py

**Future Improvements**
Convert into a Flask web app with interactive frontend
Add user login and personalized recommendations
Integrate with IMDb / TMDB API for live movie data

NOTE : Similarity_dict.pkl and movie_dict.pkl are not included due to github size limits.
       Run the Scripts to generate them locally