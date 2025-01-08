# README

This project combines a web scraper and a machine learning model to analyze and predict outcomes in the English Premier League (EPL). The scraper collects detailed match and player statistics from [FBref](https://fbref.com), while the prediction model leverages this data for predictive analytics.

## Overview
This project automates the data collection process from FBref and uses that data to build a machine learning model for soccer analytics. The scraping script collects match statistics such as goals, shots, fouls, and other key metrics. The prediction model processes this data to forecast match outcomes or other insights.

## Features
- **Data Scraping**: Extract match statistics, shooting details, and other performance metrics for multiple seasons (2021-2024).
- **User-Agent Rotation**: Prevents request blocking by rotating user-agent headers.
- **Data Cleaning and Merging**: Combines data from different sources into a unified CSV for analysis.
- **Predictive Analytics**: Uses historical data to build a machine learning model for predicting match outcomes.

## Setup
### Prerequisites
- Python 3.8 or above
- Libraries:
  - `requests`
  - `pandas`
  - `BeautifulSoup` (from `bs4`)
  - `time`
  - Machine learning libraries (specified in the Jupyter notebook)

### Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```
2. Install the required Python libraries:
   ```bash
   pip install -r requirements.txt
   ```
   *(Ensure the `requirements.txt` file lists dependencies, such as `requests`, `pandas`, etc.)*

## Usage
### Web Scraper
Run the Python script to scrape EPL match data:
```bash
python epl_web_scrapper.py
```
This will save the data to a CSV file (`2021-24matches.csv`).

### Prediction Model
Open the Jupyter notebook `soccer_prediction_model.ipynb` to preprocess the data, train models, and evaluate predictions.

## Files
- **`epl_web_scrapper.py`**: Scrapes EPL data from FBref for multiple seasons.
- **`soccer_prediction_model.ipynb`**: Processes the scraped data and builds predictive models.

## Future Work
- Enhance scraping functionality for more detailed statistics.
- Implement additional predictive models.
- Automate the pipeline from scraping to model deployment.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
