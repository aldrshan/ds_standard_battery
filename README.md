# ds_standard_battery
This repo is an attempt at building a standard battey for data science and machine learnig. 
To accomplish this the five overarching steps are:
Collect
Clean
Explore
Model building
Model Deployment

For collecting data consider starting with Kafka as you will likely outgrow CSV's and spreadsheets for data collection.
Cleaning is time and labor intensive but garbage in equals garbage out.
Cleaning step 1) Remove duplicates and irrelevant data. You dont need vehicle data for 1980's caddilacs when researching new model electric vehicles.
Cleaning step 2) Fix data structures. N/A's, Typos, bad naming conventions. The goal is uniformity
Cleaning step 3) Missing data. You can drop it or input missing values based on other observations (average).
