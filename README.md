## Exploratory Data Analysis of Hotel Booking Demand Dataset
****
## Objective:
***
The main objective of this project is to explore data mining on hotel booking demands. This data analysis enabled us to see the comparison of both hotels (City and Resort) for a period of two  years.
In this analysis, we were able to see the number of people that booked each hotel at a particular time, their genders and the family make up. It also shows us the busiest time for hotel bookings, the length of time that people stayed in each hotel, and the countries that most of those hotel bookings came from.
This exploratory analysis will help the management and the stakeholders to make informed decisions on how to maximize their profits. For instance, the management would be able to know how much to be prepared for their guests at a particular time, how many staff should be on duty to serve the guests, etc. 
In summary, this dataset is used to perform research in different problems like: bookings cancellation prediction, customer segmentation, customer satiation, seasonality, among others.
***
<a id="tableofcontents"></a>
Table of Contents:
***
1. [Introduction](#intro)
2. [Methodology](#method)
3. [Dataset](#dataset)
4. [Questions to Explore](#quest)
5. [Installation:](#inst)
6. [Conclusion](#con)

<a id="intro"></a>
## Introduction:
***
This data analysis involves exploration of a large dataset relating to hotel booking demand to determine how often people cancel their bookings, how long people stay in hotels, and which months are the busiest in the year.

<a id="method"></a>
## Methodology:
***
In this project, I used Python to examine the “hotel_bookings” dataset. I imported the data by first downloading the data and saving it as a .csv file, then I used the read.csv function in Python to begin the analysis.

<a id="dataset"></a>
## Dataset:
***
We will use the Hotel Booking Demand dataset, visit here to read more about the dataset https://www.sciencedirect.com/science/article/pii/S2352340918315191#ab00

<a id="inst"></a>
## Installation:
***
The neccessary packaged and libraries to be install is contained in the Requirement.txt file, it includes:
from IPython.display import Image
!pip install pycountry
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import pycountry as pc
import matplotlib.ticker as mtick

<a id="quest"></a>
## Questions to Explore:
1. What percentage of the booking were cancelled?
2. What is the booking ratio between Resort Hotel and City Hotel?
3. What is the percentage of booking for each year?
4. Which is the busiest month for hotels?
5. From which country most guests come?
6. How Long People Stay in the hotel?
7. Which was the most booked accommodation type (Single, Couple, Family)?**

<a id="con"></a>
## Conclusion:
***
We used the dataset that contains data about hotel bookings. We cleaned and preprocessed the data and then we performed the exploratory data analysis to extract information from the data to answer the following questions:

How Many Booking Were Cancelled?

What is the booking ratio between Resort Hotel and City Hotel?

What is the percentage of booking for each year?

Which is the busiest month for hotels?

From which country most guests come?

How Long People Stay in the hotel?

Which was the most booked accommodation type (Single, Couple, Family)?

We learned that almost 35% of bookings were canceled.

More than 60% of the population booked the City hotel.

More than double bookings were made in 2016, compared to the previous year. But the bookings decreased by almost 15% next year.

Most bookings were made from July to August. And the least bookings were made at the start and end of the year.

Portugal, the UK, France, Spain and Germany are the top countries where most guests come from; more than 80% come from these 5 countries.

Most people stay for one, two, or three days.

For Resort hotel, the most popular stay duration is three, two, one, and four days respectively.

For City hotel, most popular stay duration is one, two, seven(week), and three respectively.

Couple (or 2 adults) is the most popular accommodation type. So hotels can make arrangement plans accordingly.


