# EPL_Web_Scrapper
This repository contains a comprehensive project that scrapes English Premier League (EPL) match data and uses it to build a machine learning (ML) model to predict match outcomes. The ML model leverages a Random Forest Classifier to predict results based on various match features.

Project Structure

The repository is organized as follows:

EPL_Web_Scrapper.ipynb: A Jupyter Notebook that scrapes EPL match data from a reliable source, processes it, and saves it in a usable format for machine learning.

soccer_prediction_model.ipynb: A Jupyter Notebook that:

Loads and preprocesses the scraped data.

Explores and visualizes key features.

Builds, trains, and evaluates a Random Forest Classifier to predict match outcomes.

Features of the Project

Web Scraping: Automatically collects data for multiple seasons from EPL match records, including team statistics, match results, and other relevant features.

Data Preprocessing: Cleans and processes raw data to make it suitable for ML, including feature engineering and handling missing values.

Random Forest Classifier: Implements a robust and interpretable ML model to predict outcomes such as Home Win, Draw, or Away Win.

Evaluation Metrics: Assesses the model's performance using metrics like accuracy, precision, recall, and F1-score.

Requirements

To run the project, you need the following dependencies:

Python 3.8+

Jupyter Notebook

Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn, requests, beautifulsoup4

Install the required libraries using:

pip install -r requirements.txt

How to Use

Clone this repository:

git clone https://github.com/your-username/epl-match-prediction.git
cd epl-match-prediction

Run the web scraper:

Open EPL_Web_Scrapper.ipynb in Jupyter Notebook and execute the cells to scrape EPL data.

Train the prediction model:

Open soccer_prediction_model.ipynb in Jupyter Notebook and execute the cells to preprocess the data, train the model, and evaluate its performance.

(Optional) Use the model to predict outcomes for new match data.

Results

The Random Forest model achieves a performance score of approximately X% accuracy on the test set. Detailed evaluation metrics and visualizations are available in the soccer_prediction_model.ipynb notebook.
