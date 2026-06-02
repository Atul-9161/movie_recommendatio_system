# Movie Recommendation System

This is a movie recommendation system built using Python and Streamlit.

The project recommends movies similar to the movie selected by the user. Recommendations are generated using content-based filtering and cosine similarity. Movie posters are fetched using the TMDB API.

## Technologies Used

* Python
* Pandas
* Scikit-Learn
* Streamlit
* TMDB API

## How it Works

* Movie information is processed and converted into tags.
* Tags are vectorized using machine learning techniques.
* Cosine similarity is calculated between movies.
* The top 5 most similar movies are recommended.

## Files

* `app.py` - Streamlit application
* `movie_list.pkl` - Processed movie data
* `similarity.pkl` - Similarity matrix
* `notebook.ipynb` - Data preprocessing and model building

## Run the Project

```bash
pip install -r requirements.txt
streamlit run app.py
```

## Author

Atul Mishra
ECE, NIT Agartala
