# TMDB Top Rated Movies Dataset

This project uses the TMDb API to collect information about the top-rated movies and export the results into a CSV dataset.

## Dataset

The dataset contains approximately 10,000 movies with the following columns:

- title
- overview
- release_date
- popularity
- vote_average
- vote_count

## Technologies Used

- Python
- pandas
- requests
- TMDb API

## How to Run

1. Get an API key from TMDb.
2. Replace:

```python
API_KEY = "YOUR_TMDB_API_KEY"
```

with your own key.

3. Run the notebook.

## Output

The notebook generates:

```
tmdb_top_rated_movies.csv
```

## Author

Mohammad Hafees
