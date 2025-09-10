# Mini Project: IMDB Ratings EDA


##Overview
This project explores IMDB ratings data to understand how different genres are rated by audiences.  
The main objectives were to:
- Clean and prepare the dataset
- Calculate average ratings by genre
- Group ratings into whole numbers to simplify analysis
- Plot the distribution of ratings
- Reflect on which genres consistently receive higher ratings

## Dataset
- **Source:** [Kaggle - TV and Movie Metadata with Genres and Ratings](https://www.kaggle.com/datasets/gayu14/tv-and-movie-metadata-with-genres-and-ratings-imbd)  
- **Size:** ~129,000 records before cleaning  
- **Columns used:** `movie`, `genre`, `rating`, `votes`, `runtime`, etc.  
- **Cleaning performed:**
  - Dropped 15,510 rows missing ratings
  - Dropped rows with null genres
  - Removed duplicates
  - Expanded rows so movies with multiple genres contributed to each genre separately  
- **Final dataset size:** ~114,000 rows

## Steps Taken
1. **Load & Clean Data**
   - Handled missing values and duplicates
   - Split multiple genres into individual rows
2. **Average Ratings by Genre**
   - Calculated mean rating for each genre
3. **Group Ratings**
   - Converted continuous ratings into whole-number groups (e.g., 6.0–6.9 → 6)
4. **Visualization**
   - Identified which genres tend to receive higher or lower ratings



## Findings
- **Highest-rated genres (average rating ~7+):**
  - Documentary (7.28)
  - History (7.05)
  - News (7.03)
  - Short (6.96)
  - Talk-Show (6.97)
  - Biography (6.97)
 
- **Overall distribution:**
  - Most genres cluster around a **6 average rating**
  - A few genres achieve **7**
  - Very few are below **5**

- **Reflection Answer:**  
  Genres like **Documentary, History, News, and Biography** consistently receive higher ratings. This may be becaue viewers prefer fact based genres 







