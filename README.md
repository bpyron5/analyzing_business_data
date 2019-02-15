For our project, our group incorporated elements from three seperate projects (specified below) to create a tool that would allow our client to guage the affluency of a particular neighborhood (identified by ZIP code) based on the data made available on Yelp.

Executive Summary:

Our client, New Light Technologies, tasked us with determining the affluence of a ZIP code using price data from the popular restaurant and business review platform, Yelp. We used a public business dataset provided by Yelp to set our features and the home values provided by Zillow as a proxy for the zip code affluency. After feature engineering, exploratory data analysis, and modeling we conclude that Yelp business data does contain signal to predict neighborhood affluence. Sparse data coverage, possibility of selection bias, and incomplete business data were a few of the challenges that we ran into that prevented us from from building out a more robust model.



Below are the three mandates that we incorporated into our client project:

Problem 4: Extracting Building Values from Zillow

Problem Statement:

During a disaster, it is important to model and estimate the potential or forecasted effect of the event, including the projected/forecasted damage.
Existing indicators of forecasted damage include number of structures within the affected area, number of people in the area, number of households, demographics of the impacted population, etc.
This project will add an additional indicator: the value of the properties in the affected area. Property values can be estimated according to the market price of houses.
In this project, the students will leverage property market prices published in different real-estate websites (e.g. Zillow), according to zip codes.
The tool will allow the user to automatically search for the mean, median, min, max and average value of the properties in each zip code area.
The objective is not to download the database from these sources. Rather, it should allow the user to feed the code with a list of affected areas (zip codes) as input, and retrieve the current (or historical, annual, monthly, quarterly) property values.


Problem 7: Utilizing Yelp cost estimates for estimating neighborhood affluency

Problem Statement: This tool will estimate the affluence of a neighborhood based on the number of $ of businesses and services (according to Yelp) in a given neighborhood. ($, $$, $$$) This tool will expect to get, as an input, a list of zip codes or names of neighborhoods and will estimate the wealth of the locality. While traditional methods typically estimate wealth of a locality based on demographic characteristics (e.g. income or unemployment rate), the novelty of this approach is in its use of big data related to commercial activity and cost of product and services as an indicator for affluency.


Problem 8: Utilizing Yelp data to estimate the number of businesses in a given locality and categorizing them according to FEMA's seven lifelines

Problem Statement: Prior to and during a disaster, it is important to understand the projected and actual effects of the event on the community, including its economic effects on critical services. FEMA has identified seven â€œlifelinesâ€ that require attention during a disaster: (1) safety and security; (2) Food, water, sheltering; (3) Health and medical; (4) Energy (power, fuel); (5) Communications; (6) Transportation; (7) hazardous waste. This tool will utilize Yelp to estimate the effects of the event on each of the seven lifelines. This can include the number of businesses or services in each category or even, if available, their status (if provided by users and reviews in Yelp). The tool will search for relevant data and categorize it according to a list of impacted neighborhoods or a list of affected zip codes. It will provide an estimation of the potential impact of the event, at least according to the data available in Yelp.


We determined the affluency of a neighborhood by extracting the median home values of zipcodes across the country made available by Zillow.  Data was segmentable by ZIP code, Greater Metro Area, and State.

Our presentation is broken into the following sections:
Client Problem 
Data Science Problems
Data Collection 
Feature Engineering
Exploratory Data Analysis
Modeling
Conclusion 

Client Problem: 

Our client, New Light Technologies, tasked us with determining the affluence of a ZIP code using price data from the popular restaurant and business review platform, Yelp. 

Data Science Problems:

Is Yelp data available to be analyzed?
Can we use available Yelp to model affluency of zip codes?
How will we measure affluency?
What model will me most optimal given the data we can collect?
How will we measure model accuracy?

Data Collection:

*Gathered Yelp and Zillow Datasets to use as X and y, respectively*

Feature Engineering:

*See Slides*

EDA:

*See Slides*

Modeling:

*See Slides*

Conclusion:

*See Slides*

