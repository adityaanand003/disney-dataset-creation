
## Key Features

- **Comprehensive Scraping:** Gathers all available Disney movie information from Wikipedia lists and individual film pages.
- **In-depth Details:** Extracts titles, directors, production studios, box office, runtime, country, and more from Wikipedia.
- **Automated Cleaning:** Cleans and standardizes the raw data for analysis, removing missing/duplicate values.
- **Ratings Enrichment:** Integrates IMDB, Rotten Tomatoes, and Metascore ratings using the OMDb API.
- **Multiple Output Formats:** Outputs data as JSON, XLSX, and Pickle files for broad analysis and visualization needs.

## Usage

Open `Dataset-Creation.ipynb` in Jupyter Notebook and follow the step-wise markdown cells. API keys (for OMDb) need to be updated inside relevant cells before running.

## Requirements

- Python 3
- Jupyter Notebook
- pandas, requests, BeautifulSoup4, lxml (see notebook for full list)

## How It Works  

1. **Scraping:**  
   - Loads Wikipedia pages for all Disney movies  
   - Extracts relevant details for over 500 films

2. **Cleaning:**  
   - Removes errors, duplicates, and incomplete entries  
   - Standardizes data fields

3. **Enrichment:**  
   - Fetches ratings from OMDb API  
   - Adds IMDB, Rotten Tomatoes & Metascore data

4. **Export:**  
   - Saves cleaned and enriched datasets in various formats (JSON, Excel, Pickle)

## Dataset Contents

Each movie entry may contain:
- Title, Director, Writers, Cast, Production company
- Box office, Budget, Release date, Runtime
- Ratings (IMDB, Rotten Tomatoes, Metascore)
- Country, Language


