# Data-Curation-Draft

### Dataset
Scraped files from the movie database

### Version
Updated a month ago

### Variables
index- Unique identifier for each record
adult- Indicates if the movie is adult content (True/False)
original_language-	Original language of the movie (e.g., 'en', 'hi', 'es')
original_title-	Original title of the movie
popularity-	Popularity score calculated by TMDB (higher = more popular)
release_date- Movie release date (YYYY-MM-DD format)
video- Indicates if it's a video release
vote_average-	Average user rating (0-10 scale)
vote_count- Total number of user votes/ratings
genre_ids- List of genre IDs associated with the movie

### Files Included
tmdb_movies_cleaned.csv: Cleaned movie metadata including ratings, popularity, votes, genres, and release dates.
genre_mapping.json: Mapping of TMDB genre IDs to genre names.
starter_notebook.ipynb: Starter notebook for exploratory data analysis and visualization.
README.md: Detailed documentation, data source information, and usage instructions.
