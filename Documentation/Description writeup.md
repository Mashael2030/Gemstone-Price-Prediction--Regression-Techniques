# NYC Taxi and Limousine Commission - TLC Trip Data 


## Abstract
The goal of this project is to apply Linear Regression algorithms on Tlc Trip data  , to predict the fare amount of trips based on the features  (VendorID, Passenger count,Trip distance , etc.). I worked with data that I have been analyzing the dataset.  After getting the data we start to clean them remove nulls values, fill null discount with zeros and extract numbers from string. After that we started to explore the dataset and split the data into %60 train/%20validation, and %20 for the test .Finally we tried different types of models to find the best one that fit our data which is simple Linear Regression .

## Data
The data that will be used in this project has been extracted from Tlc Trip Record Data website (https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page). It includes data such as: (Trip distance, Fare amount , Tip amount , etc.) for each course. It includes 19 features and more than 10 millions , and below is the description of each one:


| Feature               | Description                                                                     |
|-----------------------|---------------------------------------------------------------------------------|
| VendorID              |	A code indicating the TPEP provider that provided the recorde (1= Creative Mobile Technologies, LLC; 2= VeriFone Inc).
| tpep_pickup_datetime  | The date and time when the meter was engaged.
| tpep_dropoff_datetime | The date and time when the meter was disengaged.
| Passenger_count       | The number of passengers in the vehicle.
| Trip_distance         | The elapsed trip distance in miles reported by the taximeter.
| PULocationID          | TLC Taxi Zone in which the taximeter was engaged
| DOLocationID          | TLC Taxi Zone in which the taximeter was disengaged
| RateCodeID            |The final rate code in effect at the end of the trip. 1= Standard rate,2=JFK,3=Newark,4=NassauORWestchester,5=NegotiatedFare,6=GroupRide
| Store_and_fwd_flag    | This flag indicates whether the trip record was held in vehicle memory before sending to the vendor.
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

