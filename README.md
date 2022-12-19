![Final-Intro](https://user-images.githubusercontent.com/84449238/202843080-60993278-524c-45f7-b157-597ecfc10d98.jpg)

# Taxi-Trip-Fare-Prediction-Challenge-MachineHack

![Final-Image](https://user-images.githubusercontent.com/84449238/208449023-9c6c965b-f3da-42f2-b7d4-9e87a253e5c1.jpg)

**(Image Credit:- OLA & UBER)**

**1) Problem Statement:-**

This hackathon will try to address the challenges faced by taxi operators in quoting the right fare to customers before starting the trip. However, the details are shared with taxi drivers or operators related to the trip, they find it difficult to quote the right fare because of uncertainties and calculation complexities. The same issue is faced by passengers as well because of inaccurate or irrelevant fares quoted. To find a solution for this, this hackathon provides a historical dataset to participants that includes records of taxi trip details and fares of those trips. Using this dataset, the participants need to build machine learning models for predicting the trip fare based on the given other useful features of the trip.

**2) Task:-**

From available dataset, finding the best set of features from the dataset, building a machine learning model to predict trip fare based on other trip features.

**3) About the Dataset:-** Dataset contains following files,

**3.1) Train:-** 35000 rows x 20 columns 

**3.2) Test:-** 15000 rows x 19 columns

**3.3) Data description:-**

**a) Trip_distance:** The elapsed trip distance in miles reported by the taximeter.

**b) Rate_code:** The final rate code is in effect at the end of the trip. 1= Standard rate,2=JFK,3=Newark, 4=Nassau or Westchester, 5=Negotiated fare,6=Group ride

**c) Storeandfwd_flag:** This flag indicates whether the trip record was held in vehicle memory before sending it to the vendor and determines if the trip was stored in the server and forwarded to the vendor. Y= store and forward trip N= not a store and forward trip

**d) Payment_type:** A numeric code signifying how the passenger paid for the trip. 1= Credit card,2= Cash, 3= No charge, 4= Dispute, 5= Unknown, 6= Voided trip

**e) Fare_amount:** The time-and-distance fare calculated by the meter

**f) Extra:** Miscellaneous extras and surcharges

**g) Mta_tax:** $0.50 MTA tax that is automatically triggered based on the metered rate in use

**h) Tip_amount:** Tip amount credited to the driver for credit card transactions

**i) Tolls_amount:** Total amount of all tolls paid in the trip

**j) Imp_surcharge:** $0.30 extra charges added automatically to all rides

**k) Total_amount:** The total amount charged to passengers. Does not include cash tips

**l) Pickuplocationid:** TLC Taxi Zone in which the taximeter was engaged

**m) Dropofflocationid:** TLC Taxi Zone in which the taximeter was disengaged

**n) Year:** The year in which the taxi trip was taken

**o) Month:** The month on which the taxi trip was taken

**p) Day:** The day on which the taxi trip was taken

**q) Day_of_week:** The day of the week on which the taxi trip was taken

**r) Hour_of_day:** Used to determine the hour of the day in 24 hours format

**s) Trip_duration:** The total duration of the trip in seconds

**3.4) Output feature (Target feature):-**

**a) calculated_total_amount:** The total amount the customer has to pay for the taxi

**4) Evaluation metric:-** The submission will be evaluated using the RMSE metric

**5) Public and Private Split:-**

a) This hackathon supports private and public leaderboards.

b) The public leaderboard is evaluated on 30% of Test data

c) The private leaderboard will be made available at the end of the hackathon, which will be evaluated on 100% Test data

# Summary

**a) Best Submission Score:-**

**1) Public Leaderboard :-** 19.45867

**2) Private Leaderboard :-** 19.16595

**b) Best Model:-** Histogram Gradient Boosting Regression

![Public-Leaderboard](https://user-images.githubusercontent.com/84449238/208469594-1c380606-5b36-4514-b936-ad92ba7d2ebd.jpg)

![Private-Leaderboard](https://user-images.githubusercontent.com/84449238/208469629-0ccc112f-f5bf-4d15-9b9b-ce0b893576f0.jpg)

**c) Competition Link:-** https://machinehack.com/hackathons/iiit_nr_taxi_trip_fare_prediction_challenge/leaderboard

**d) Rank Scored:-**

a) **07** out of **441** registered participants (Public Leaderboard)

b) **61** out of **441** registered participants (Private Leaderboard)
