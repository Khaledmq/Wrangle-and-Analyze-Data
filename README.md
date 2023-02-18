Wrangle-and-Analyze-Data
This project is a data wrangling and analysis project, which involves gathering data from various sources, assessing its quality and tidiness, cleaning the data and performing exploratory data analysis on it.

The project is divided into three main parts:

Data Gathering: In this part, we gather data from different sources, including CSV, TSV, XLSX files, API, and web scraping.
Data Assessing: In this part, we assess the gathered data for quality and tidiness issues.
Data Cleaning: In this part, we clean the assessed data by addressing the quality and tidiness issues found in the previous step.
Technologies Used
Python 3.9
Jupyter Notebook
Pandas
NumPy
Requests
Tweepy
Beautiful Soup
Installation
Clone this repository using git clone https://github.com/<USERNAME>/Wrangle-and-Analyze-Data.git
Install the required libraries by running pip install -r requirements.txt
Open the Jupyter notebook by running jupyter notebook command in the terminal and then open Wrangle and Analyze Data.ipynb.
File Descriptions
Wrangle and Analyze Data.ipynb: This is the main notebook where the data wrangling and analysis is performed.
twitter-archive-enhanced.csv: The WeRateDogs Twitter archive that contains basic tweet data for all 5000+ of their tweets, but not everything.
image_predictions.tsv: The tweet image predictions, i.e., what breed of dog (or other object, animal, etc.) is present in each tweet according to a neural network.
tweet_json.txt: Additional data gathered through Twitter's API.
twitter_archive_master.csv: The final cleaned data that is produced after data wrangling.
Data Sources
WeRateDogs Twitter archive
Tweet image predictions
Additional data gathered through Twitter's API
Results
The results of the data wrangling and exploratory data analysis can be found in the Jupyter notebook. The findings are presented in a clear and concise manner, with visualizations included to aid understanding.

Acknowledgements
This project was completed as part of the Udacity Data Analyst Nanodegree program. The data was provided by WeRateDogs (@dog_rates) on Twitter, and the code for gathering additional data from Twitter's API was provided by Udacity.
