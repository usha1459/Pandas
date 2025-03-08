# Movie Dataset Analysis

## Overview

This project involves analyzing a dataset of 1000 movies using Pandas and NumPy. The dataset includes information about movie names, genres, release years, IMDb ratings, and revenue. Various filtering, sorting, and statistical operations have been performed on the dataset to extract insights.

## Dataset Description

The dataset consists of the following columns:

- **Movie Name**: The title of the movie.
- **Genre**: The category of the movie (e.g., Action, Comedy, Horror, etc.).
- **Release Year**: The year in which the movie was released.
- **IMDb Rating**: The IMDb rating of the movie.
- **Revenue**: The total box office earnings of the movie.

## Operations Performed

### 1. Filtering Data

- Selecting movies in the "Action" genre.
- Selecting movies released after the year 2000.
- Selecting movies with an IMDb rating greater than 8.5.

### 2. Selecting Specific Columns

- Extracting only "Movie Name" and "Genre" columns.
- Selecting movies released between 1990 and 2010.

### 3. Statistical Analysis

- Counting the number of movies in each genre.
- Finding the highest IMDb-rated movie.
- Calculating the average IMDb rating of all movies.
- Computing the total box office collection of all movies.

### 4. Sorting and Ranking

- Ranking movies based on IMDb ratings.
- Sorting movies by release year in descending order.

### 5. Handling Duplicates and Data Cleaning

- Identifying duplicate movie names.
- Removing duplicate movie names.
- Replacing "Sci-Fi" with "Science Fiction" in the genre column.

### 6. Data Extraction

- Selecting the first 10 movies from the dataset.

## Requirements

To run this analysis, you need:

- Python 3.x
- Pandas
- NumPy

Install dependencies using:

```bash
pip install pandas numpy
```

## Usage

Run the script using:

```bash
python movies_analysis.py
```

## Output

The script provides:

- Filtered and sorted datasets.
- Statistical summaries.
- Insights on IMDb ratings, revenues, and genres.


