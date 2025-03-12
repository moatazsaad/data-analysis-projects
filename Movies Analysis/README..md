# Movies Data Processing and Analysis  

## **1. Movies-Dealing with API, JSON Files.ipynb**  
- Retrieves movie data from **The Movie Database (TMDb) API** using `requests`.  
- Parses JSON responses into a **Pandas DataFrame**.  
- Normalizes nested JSON structures into flat tables for easier analysis.  

## **2. Movies-Data Cleaning.ipynb**  
- Cleans the dataset obtained from the API.  
- Converts **stringified JSON columns** into usable formats.  
- Flattens nested columns for structured analysis.  
- Cleans **numerical and object columns**, handling missing values.  
- Removes duplicates and prepares the dataset for further analysis.  

## **3. Movies-Merging, Transforming Data.ipynb**  
- Loads **credits.csv** and merges it with the cleaned movie dataset.  
- Extracts key information from stringified JSON columns related to **cast and crew**.  
- Identifies director names from crew data.  
- Transforms and saves the dataset for future use.  

## **4. Movies-EDA.ipynb**  
- Conducts **exploratory data analysis (EDA)** on the merged dataset.  
- Analyzes features such as **budget, revenue, ratings, genres, franchises, directors, and actors**.  
- Uses **histograms, bar plots, and word clouds** for data visualization.  
- Answers key questions on **successful directors, actors, and trends over time**.  
- Examines genre popularity across different decades.  

## **5. Working with pandas sql.ipynb**  
- Creates four DataFrames (**movies, votes, genres, and prod**) from the loaded JSON data.  
- Saves them as tables in an SQLite database (`movies.db`).  
- Demonstrates **loading data from SQLite** into Pandas DataFrames.  
- Executes **SQL queries** using `pd.read_sql`, including operations like counting, summing, selecting, joining, and filtering.  
