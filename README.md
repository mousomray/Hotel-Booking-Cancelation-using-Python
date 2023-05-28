# Hotel Booking Cancelation using Python

# Business Problem 
In recent years, City Hotel and Resort Hotel have seen high 
cancellation rates. Each hotel is now dealing with a number of issues 
as a result, including fewer revenues and less than ideal hotel room 
use. Consequently, lowering cancellation rates is both hotels' 
primary goal in order to increase their efficiency in generating 
revenue, and for us to offer thorough business advice to address this 
problem. The analysis of hotel booking cancellations as well as other 
factors that have no bearing on their business and yearly revenue 
generation are the main topics of this report.

# Assumptions
1. No unusual occurrences between 2015 and 2017 will have a 
substantial impact on the data used.
2. The information is still current and can be used to analyze a hotel's 
possible plans in an efficient manner. 
3. There are no unanticipated negatives to the hotel employing any 
advised technique. 
4. The hotels are not currently using any of the suggested solutions. 
5. The biggest factor affecting the effectiveness of earning income is 
booking cancellations. 
6. Cancellations result in vacant rooms for the booked length of time. 
7. Clients make hotel reservations the same year they make 
cancellations.

# Research Question
1. What are the variables that affect hotel reservation cancellations? 
2. How can we make hotel reservations cancellations better? 
3. How will hotels be assisted in making pricing and promotional 
decisions?

# Hypothesis 
1. More cancellations occur when prices are higher. 
2. When there is a longer waiting list, customers tend to cancel more 
frequently. 
3. The majority of clients are coming from offline travel agents to make 
their reservations

# I worked on this project 
* Data collection
* Data Loading
* Import Libraries
* Data cleaning and processing
* Data Analysis and Visualization 
* Final Insights

# Import Libraries 
Imported these libraries which are very necessary in this project :-   
* import pandas as pd 
* import numpy as np 
* import matplotlib.pyplot as plt 
* import seaborn as sns
* import warnings
* warnings.filterwarnings('ignore')

# Data cleaning and processing 
After collecting csv files and loading it into Python performed various activities like removing missing values, remove unimportant rows and columns and fixing type errors that can be easily analyzed.

# Data Analysis and Visualization 
* Created count plot between hotel reservation canceled and not canceled. 
* Created vertical Bar chart with Reservation status in Resort Hotel and City Hotel.
* Created Line chart with average daily rate in City and Resort hotel. 
* Created Vertical Bar chart with reservation status per month Canceled and Not Canceled. 
* Created vertical Bar chart for to see ADR per month. 
* Created pie chart to analysis Top 10 countries with reservation canceled. 
* Created Line chart with Average daily rate between Hotel canceled and not canceled.  

# Final Insights 

* Resort hotels and city hotels combined 62.86% clients did not cancel their reservations and 37% clients canceled their reservations. This 37% cancellation significantly affects on hotel earnings. 

* The reservation rate of city hotels is higher than the reservation rate of resort hotels. So it can be said that the demand of city hotels is more than resort hotels. The main reason for this is that resort hotels are more expensive than city hotels.

* City hotel rates are lower on certain days or holidays and even lower on other days. But resort hotel rates go up on holidays or weekends and are higher than city hotels on other days too. 


* Month of August has the highest number of reservations as well as cancellation of large amount reservations. Again, the number of cancellations in the month of January is the highest.

* Hotel cancellations were highest when hotel prices were high and cancellation rates were low when prices were low. This implies that, there is a significant relationship between hotel price and hotel cancellation.

* Portugal has the highest number of cancellations among all countries. 

* Around 47% of the clients come from online travel agencies. whereas 16% come from groups. Only 10% of clients book hotels directly by visiting them and making  reservations.

* Reservations are canceled when the average daily rate is higher than what it would have been without cancellations. From all the above analysis it is clear that higher prices lead to higher cancellations.

 
        
