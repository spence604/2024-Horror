# Movie Dataset Enrichment

## Overview
This project involves enriching a movie dataset by scraping additional details such as IMDb ratings, Rotten Tomatoes scores, budget, and box office gross using the OMDb API and IMDbPy library. The goal is to enhance the dataset for better analysis and visualization in Tableau.

## Features
- Fetches and appends IMDb ratings and Rotten Tomatoes scores for each movie in the dataset.
- Retrieves budget and box office gross information.
- Handles various data types and potential errors during the data retrieval process.
- Saves the enriched dataset to a new CSV file for further analysis.

## Requirements
- Python 3.10 or higher
- Pandas
- Requests
- IMDbPy

You can install the required packages using pip:
```bash
pip install pandas requests IMDbPY
