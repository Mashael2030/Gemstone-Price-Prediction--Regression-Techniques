# NYC Taxi and Limousine Commission - TLC Trip Data 


## Abstract
The goal of this project is to apply Linear Regression algorithms on Tlc Trip data  , to predict the fare amount of trips based on the features  (VendorID, Passenger count,Trip distance , etc.). I worked with data that I have been analyzing the dataset.  After getting the data we start to clean them remove nulls values, fill null discount with zeros and extract numbers from string. After that we started to explore the dataset and split the data into %60 train/%20validation, and %20 for the test .Finally we tried different types of models to find the best one that fit our data which is simple Linear Regression .

## Data
The data that will be used in this project has been extracted from Tlc Trip Record Data website (https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page). It includes data such as: (Trip distance, Fare amount , Tip amount , etc.) for each course. It includes 19 features and more than 10 millions , and below is the description of each one:


| Feature               | Description                                                                     |
|-----------------------|---------------------------------------------------------------------------------|
| VendorID              |	A code indicating the TPEP provider that provided the re
|                       | 1= Creative Mobile Technologies, LLC; 2= VeriFone Inc.
| Description           |	Description of course content
| Price                 | The original price
| Discount              | The price after discount
| Rating                | The price after discount
| Reviews              	| The total number of reviews
| Trainer               | Trainer’s name
| Total_hours           | Duration of the course
| Total_lectures        | Number of lectures
| level                 | Course level

* 10 features
* +9k rows

## Algorithms
Our steps in this project was:
1. Problem understanding
2. Data gathering by scrapping 
3. Data exploration and visualization
4. Feature engineering
5. Starting training and validation our data on different models. 

## Tools
- Python and Jupyter Notebook
- Numpy and Pandas for data manipulation
- Matplotlib and Seaborn for plotting visuialization
- BeautifulSoup and selenium for web scraping
- Sklearn for ML algorithms
- HTML/CSS

## Communication
In addition to the slides and visuals presented, we will share our work on our Github accounts
* https://github.com/RawabiKhalaf/curses-rating-prediction/blob/main/Source_code.ipynb

