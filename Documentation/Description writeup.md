# NYC Taxi and Limousine Commission - TLC Trip Data 


## Abstract
The goal of this project is to apply Linear Regression algorithms on Tlc Trip data  , to predict the fare amount of trips based on the features  (VendorID, Passenger count,Trip distance , etc.). I worked with data that I have been analyzing the dataset.  After getting the data we start to clean them remove nulls values, fill null discount with zeros and extract numbers from string. After that we started to explore the dataset and split the data into %60 train/%20validation, and %20 for the test .Finally we tried different types of models to find the best one that fit our data which is simple Linear Regression .

## Data
The data that will be used in this project has been extracted from Tlc Trip Record Data website (https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page). It includes data such as: (Trip distance, Fare amount , Tip amount , etc.) for each course. It includes 19 features and more than 10 millions , and below is the description of each one:


| Feature               | Description                                                                     |
|-----------------------|---------------------------------------------------------------------------------|
| VendorID              |	A code indicating the TPEP provider that provided the recorde (1= Creative Mobile Technologies,2= VeriFone Inc).
| tpep_pickup_datetime  | The date and time when the meter was engaged.
| tpep_dropoff_datetime | The date and time when the meter was disengaged.
| Passenger_count       | The number of passengers in the vehicle.
| Trip_distance         | The elapsed trip distance in miles reported by the taximeter.
| PULocationID          | TLC Taxi Zone in which the taximeter was engaged
| DOLocationID          | TLC Taxi Zone in which the taximeter was disengaged
| RateCodeID            | The final rate code in effect at the end of the trip. ( 1= Standard rat, 2=JFK, 3=Newark , 4=NassauORWestchester , 5=NegotiatedFare, 6=GroupRide )
| Store_and_fwd_flag    | This flag indicates whether the trip record was held in vehicle memory before sending to the vendor.(Y= store and forward trip N= not a store&forward ) 
| Payment_type          | A numeric code signifying how the passenger paid for the trip. 1= Credit card,2= Cash,3= No charge,4= Dispute,5= Unknown,6= Voided trip
| Fare_amount           | The time-and-distance fare calculated by the meter.
| Extra                 | Miscellaneous extras and surcharges. Currently, this only includes the $0.50 and $1 rush hour and overnight charges.
| MTA_tax               | $0.50 MTA tax that is automatically triggered based on the metered rate in use.
| Improvement_surcharge | $0.50 MTA tax that is automatically triggered based on the metered rate in use.
| Tip_amount            | This field is automatically populated for credit card tips. Cash tips are not included.
| Tolls_amount          | Total amount of all tolls paid in trip.
| Total_amount          | The total amount charged to passengers. Does not include cash tips.

* 18 features
* 10M rows

## Algorithms
Our steps in this project was:
1. Problem understanding
2. Data Collection
3. Data exploration and visualization
4. Feature engineering
5. Starting training and validation our data on different models. 

## Tools
- Python and Jupyter Notebook
- Numpy and Pandas for data manipulation
- Matplotlib and Seaborn for plotting visuialization
- Sklearn for ML algorithms


## Communication
In addition to the slides and visuals presented, we will share our work on our Github accounts
* 

