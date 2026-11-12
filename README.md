# Movie Recommender System

A content-based movie recommendation application built using Python and Streamlit. It recommends five movies similar to the selected movie using **CountVectorizer** and **Cosine Similarity**.

## Live Demo

**[Movie Recommender System](https://movie-recommender-system-vvranjan.streamlit.app/)**

## Technologies Used

- Python
- Streamlit
- Pandas
- Scikit-learn
- TMDB API
- Pickle

## Features

- Select a movie from the available movie collection.
- Get five similar movie recommendations.
- View movie posters fetched using the TMDB API.

## How to Run Locally

1. Clone the repository:

   ```bash
   git clone https://github.com/vvranjan/movie-recommender-system.git
   cd movie-recommender-system
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Configure your TMDB API key in `.streamlit/secrets.toml`:

   ```toml
   TMDB_API_KEY = "your_tmdb_api_key"
   ```

4. Run the application:

   ```bash
   streamlit run app.py
   ```

## Author

**Vaibhav V. Ranjan**

