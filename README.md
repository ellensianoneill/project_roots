# Project Roots 

***Example of engineering and analysis performed on market survey data for the Project Roots initative.***

Files:

1. **Jupyter Notebook** | market_survey_engineering.ipyb

   Uses Google API to pull data from Google Sheet, perform data cleansing steps, and insert output into new Google Sheet tabs.
   Using Python, both tall and wide datasets have been generated to aid with data analysis in alternative tooling (e.g. Tableau).

   The following tutorial was used to establish connection to Google Sheets
   https://medium.com/analytics-vidhya/how-to-read-and-write-data-to-google-spreadsheet-using-python-ebf54d51a72c

2. **Jupyter Notebook** | market_survey_analysis.ipyb

   Uses data analytical techniques to gain insight into the dataset (incl. histograms and correlation matrices).

3. **Environment** | environment.yaml

   File outlines the name of the environment used for this project, as well as the dependencies that required installation.
   Using the conda env export --from-history flag, this environemt file will work across all platforms.
