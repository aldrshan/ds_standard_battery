# ds_standard_battery
This repo is an attempt at building a standard battey for data science and machine learnig. 
To accomplish this the five overarching steps are:
Collect
Clean
Explore
Model building
Model Deployment

For collecting data consider starting with Kafka or similar for a data stream and a DB for data storage as you will likely outgrow CSV's and spreadsheets for data collection.

Cleaning is time and labor intensive but garbage in equals garbage out.

** Cleaning step 1) ** Remove duplicates and irrelevant data. You dont need vehicle data for 1980's caddilacs when researching new model electric vehicles.

** Cleaning step 2) ** Fix data structures. N/A's, Typos, bad naming conventions. The goal is uniformity

** Cleaning step 3) ** Missing data. You can drop it or input missing values based on other observations (average).

** Cleaning step 4) ** Outliers. Exercise caution when considering removing outliers as some of them provide more insight to your data than the average data point. 

** Cleaning step 5) ** Data validation. Does the data make sense? Does the data follow the appropriate rules for its field?
Can you say this about the data?

    Validity. The degree to which your data conforms to defined business rules or constraints.
    Accuracy. Ensure your data is close to the true values.
    Completeness. The degree to which all required data is known.
    Consistency. Ensure your data is consistent within the same dataset and/or across multiple data sets.
    Uniformity. The degree to which the data is specified using the same unit of measure.
    
Consider a cleaning tool such as https://openrefine.org/ it's free and open source!
