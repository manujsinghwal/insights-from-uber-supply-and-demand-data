# Insights From Uber Supply And Demand Data
\
![image](https://github.com/manujsinghwal/insights-from-uber-supply-and-demand-data/assets/40256851/159c5ef8-e792-42ad-ac54-61242a56831c)
\
The data set provided [uber.csv](https://drive.google.com/file/d/1eh_gE-4NdmYNbmxGAuiJ0B_ibURtoWwe/view?usp=sharing) 

Using the provided dataset, answer the following asked questions.

1. Which date had the most completed trips during the two week period?
2. Which hour of the day had the most requests during the two week period?
3. What percentages of all zeroes during the two week period occurred on 5.weekend (Friday at 5 pm to Sunday at 3 am)? Tip: The local time value is the start of the hour (e.g. 15 is the hour from 3:00pm - 4:00pm)
4. What is the weighted average ratio of completed trips per driver during the two week period? Tip: "Weighted average" means your answer should account for the total trip volume in each hour to determine the most accurate number in whole period.
5. True or False: Driver supply always increases when demand increases during the two week period. Tip: Visualize the data to confirm your answer if needed.
6. If you could add 5 drivers to any single hour of every day during the two week period, which hour should you add them to? Hint: Consider both rider eyeballs and driver supply when choosing
7. True or False: There is exactly two weeks of data in this analysis
8. Looking at the data from all two weeks, which time might make the most sense to consider a true "end day" instead of midnight? (i.e when are supply and demand at both their natural minimums) Tip: Visualize the data to confirm your answer if needed.

# Data Description
To answer the above question, use the dataset from the file uber.csv. For example, consider the row 11 from this dataset:
\
\
![image](https://github.com/manujsinghwal/insights-from-uber-supply-and-demand-data/assets/40256851/e55d0f1b-3ca7-444b-a1e8-93642ce41e22)
\
\
This means that during the hour beginning at 4pm (hour 16), on September 10th, 2012, 11 people opened the Uber app (Eyeballs). 2 of them did not see any car (Zeroes) and 4 of them requested a car (Requests). Of the 4 requests, only 3 complete trips actually resulted (Completed Trips). During this time, there were a total of 6 drivers who logged in (Unique Drivers).
