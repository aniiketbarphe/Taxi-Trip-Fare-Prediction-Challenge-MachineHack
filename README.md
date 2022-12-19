![Final-Intro](https://user-images.githubusercontent.com/84449238/202843080-60993278-524c-45f7-b157-597ecfc10d98.jpg)

# Taxi-Trip-Fare-Prediction-Challenge-MachineHack

![Final-Image](https://user-images.githubusercontent.com/84449238/208449023-9c6c965b-f3da-42f2-b7d4-9e87a253e5c1.jpg)

**(Image Credit:- OLA & UBER)**
**1) Problem Statement:-**

This hackathon will try to address the challenges faced by taxi operators in quoting the right fare to customers before starting the trip. However, the details are shared with taxi drivers or operators related to the trip, they find it difficult to quote the right fare because of uncertainties and calculation complexities. The same issue is faced by passengers as well because of inaccurate or irrelevant fares quoted. To find a solution for this, this hackathon provides a historical dataset to participants that includes records of taxi trip details and fares of those trips. Using this dataset, the participants need to build machine learning models for predicting the trip fare based on the given other useful features of the trip.

**2) Task:-**

From available dataset, finding the best set of features from the dataset, building a machine learning model to predict trip fare based on other trip features.

**3) About the Dataset:-** Dataset contains following files,

**a) Train:-** 35000 rows x 20 columns 

**b) Test:-** 15000 rows x 19 columns

**c) Data description:-**

**1) Trip_distance:** The elapsed trip distance in miles reported by the taximeter.

**2) Rate_code:** The final rate code is in effect at the end of the trip. 1= Standard rate,2=JFK,3=Newark, 4=Nassau or Westchester, 5=Negotiated fare,6=Group ride

**3) Storeandfwd_flag:** This flag indicates whether the trip record was held in vehicle memory before sending it to the vendor and determines if the trip was stored in the server and forwarded to the vendor. Y= store and forward trip N= not a store and forward trip
Payment_type: A numeric code signifying how the passenger paid for the trip. 1= Credit card,2= Cash, 3= No charge, 4= Dispute, 5= Unknown, 6= Voided trip
Fare_amount: The time-and-distance fare calculated by the meter
Extra: Miscellaneous extras and surcharges.
Mta_tax: $0.50 MTA tax that is automatically triggered based on the metered rate in use.
Tip_amount: Tip amount credited to the driver for credit card transactions.
Tolls_amount: Total amount of all tolls paid in the trip.
Imp_surcharge: $0.30 extra charges added automatically to all rides
Total_amount: The total amount charged to passengers. Does not include cash tips
Pickuplocationid: TLC Taxi Zone in which the taximeter was engaged
Dropofflocationid: TLC Taxi Zone in which the taximeter was disengaged
Year: The year in which the taxi trip was taken.
Month: The month on which the taxi trip was taken.
Day: The day on which the taxi trip was taken.
Day_of_week: The day of the week on which the taxi trip was taken
Hour_of_day: Used to determine the hour of the day in 24 hours format
Trip_duration: The total duration of the trip in seconds
calculated_total_amount: The total amount the customer has to pay for the taxi.

Evaluation:-

The submission will be evaluated using the RMSE metric. One can use ‘np. sqrt (Mean Squared Error)’ to calculate the same. [mean_squared_error(y_true, y_pred, squared=False)]
This hackathon supports private and public leaderboards
The public leaderboard is evaluated on 30% of Test data
The private leaderboard will be made available at the end of the hackathon which will be evaluated on 100% of Test data
The Final Score represents the score achieved based on the Best Score on the public leaderboard
