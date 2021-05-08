# NYC Taxi Trip Duration

New York City’s 12,779 yellow medallion taxicabs comprise a $1.8 billion industry serving about 240 million passengers a year. Information on New York’s cabs attracts a broad audience due to their central transportation role and their prominence in Manhattan traffic. Exploiting an understanding of taxi trip durations and the ability to predict taxi durations could present valuable insights to city planners and the people of New York. Hence, this problem statement is of great significance. 

The Kaggle competition named “New York City Taxi Trip Duration” consists of the 2016 NYC Yellow Cab trip record data, which was originally published by the NYC Taxi and Limousine Commission (TLC). This competition demands us to build a model that predicts the total ride duration of taxi trips in New York City. Thus, the problem statement is defined as follows: determine best predictors of NYC taxi trip durations, and build a multivariate taxi trip duration predictor.

<img src="assets/nyc-taxi.jpeg">

## Model Performance 
__Final Model:__ XGBoost model with K-fold Cross Validation 

__Result (Kaggle Public Leaderboard):__ RMSE 0.37356, 79th position (top 6.3%)

__Result (Kaggle Private Leaderboard):__ RMSE 0.37112, 116th position (top 9.2%)

## Set Up

### PREREQUISITES

* Ensure Python3 and pip is downloaded and added to system environment variables.

* The following packages are required: pandas, numpy, seaborn, datetime, matplotlib, xgboost, and sklearn. Please ensure they are downloaded through the command ```pip install <package_name>```


### INSTRUCTIONS TO RUN CODE

* Open the Python Notebook titled Main.ipynb on Google Colab or Jupyter Notebook

* The dataset required for the Notebook can be easily imported by running the cells containing the ```pd.read_csv()``` statements since the datasets are hosted on Firebase. In case there is something wrong with the Firebase server, the datasets can be manually imported into the Notebook's runtime. Here are the URLs for the datasets used:

  * NYC Taxi Trip Duration Dataset: https://www.kaggle.com/c/nyc-taxi-trip-duration/data
  * OSRM Dataset: https://www.kaggle.com/oscarleo/new-york-city-taxi-with-osrm
  * Weather Dataset: https://www.kaggle.com/mathijs/weather-data-in-new-york-city-2016

* All code cells must be executed sequentially. 
