# Movie Recommendation System

## Project Overview
This project involves building a movie recommendation system using collaborative filtering and content-based filtering techniques. It utilizes movie rating data to suggest movies to users based on their preferences. The project is implemented in Python and consists of two Jupyter notebooks:

1. **Content_Base.ipynb** - Implements a content-based recommendation system.
2. **Datamining_recommender_systems.ipynb** - Implements a collaborative filtering-based recommendation system.

## Dataset
The project utilizes the following datasets:
- **movies.csv**: Contains information about movies, including titles and release years.
- **ratings.csv**: Contains user ratings for various movies, including user ID, movie ID, rating, and timestamp.

## Implementation Details

### 1. Content-Based Filtering (Content_Base.ipynb)
- Loads movie and rating datasets using Pandas.
- Preprocesses movie titles by extracting release years and cleaning text.
- Uses the movie descriptions and metadata to compute similarities between movies.
- Recommends movies to users based on the similarity of movie content.

### 2. Collaborative Filtering (Datamining_recommender_systems.ipynb)
- Loads the same datasets as the content-based model.
- Uses collaborative filtering techniques, specifically user-based and item-based filtering.
- Computes user similarity using cosine similarity and recommends movies based on user preferences.

## Dependencies
Ensure you have the following Python libraries installed before running the notebooks:
```bash
pip install pandas numpy matplotlib seaborn
```

## Running the Notebooks
1. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Navigate to and open `Content_Base.ipynb` or `Datamining_recommender_systems (1).ipynb`.
3. Execute the cells sequentially to generate recommendations.

## Expected Output
- Content-Based Filtering will suggest movies similar to a given movie based on features.
- Collaborative Filtering will recommend movies based on user rating patterns.