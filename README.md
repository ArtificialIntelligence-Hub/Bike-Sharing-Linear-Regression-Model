# Bike-sharing-assignment
## Created a model using linear regression to predict the demand for shared bicycles.

![image](https://media.electrive.com/2022/09/mobi_by_shaw_go_e-bikes_and_e-stations-e1662381673727.png)


## Table of Contents
* [Problem Statement](#problem-statement)
* [Business Goal](#business-goal)
* [Technologies Used](#technologies-used)
* [Insights](#insights)
* [Recommendation](#recommendation)
* [Contact](#contact)


## Problem Statement

A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.


A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 


In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands
Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.


## Business Goal 

You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## Technologies Used
- Numpy==1.23.2
- Pandas==1.5.2
- matplotlib==3.8.2
- seaborn==0.13.2
- statsmodels==0.14.1

## Insights

The graphical representations in the dataset provide valuable insights into the qualitative distributions of the data. Utilizing these visualizations, we can enhance our confidence in the model's predictions, particularly in identifying significant predictors. Key observations include:

1. **Seasonal Variation:**
   The variable "season" exhibits distinct patterns, with Fall (category 3) demonstrating the highest median, indicating heightened demand during this season, while Spring (category 1) shows the lowest median.

2. **Yearly Trends:**
   Analysis reveals that the year 2019 witnessed a higher user count compared to 2018, suggesting a potential upward trend in demand.

3. **Weekly Demand:**
   The demand for bikes appears relatively constant throughout the week, with no discernible trend in the weekday dataset. Consequently, this variable may not significantly contribute to prediction accuracy.

4. **Weather Impact:**
   Clear weather conditions consistently account for a user count ranging between 4000 to 6000, with approximately 5500 users, highlighting the stability in demand under such weather conditions.

5. **Monthly Patterns:**
   The "Mnth" variable exhibits a discernible trend, indicating its potential as a valuable predictor. Mid-months consistently register user counts above 4000, with October standing out as the month with the highest user count.

6. **Holiday Influence:**
   During holidays, there is a noticeable dip in user counts, suggesting a decrease in demand during these periods.

7. **Working Day vs. Non-Working Day:**
   The "Workingday" boxplot illustrates that the difference in bookings between working and non-working days is not substantial. Maximum bookings occur within the range of 4000 to 6000, irrespective of the working day status.

These insights, derived from the graphical analysis, provide a foundation for selecting pertinent predictor variables to enhance the predictive capabilities of the model. 


## Recommendation 

The company should prioritize certain months for its operational planning, as indicated by the data:

1. **High-Demand Months:**
   The months of January, July, September, November, and December consistently demonstrate higher demand compared to other months. The company should strategically allocate resources and plan marketing initiatives during these periods to capitalize on increased user interest.

2. **Temperature Impact:**
   There is a positive correlation between temperature and bike demand, suggesting that as temperatures rise, so does the demand. It is imperative for the company to monitor weather conditions closely and consider this variable in its planning and forecasting to ensure optimal resource allocation during periods of heightened demand.

3. **Winter Season Preparedness:**
   The data highlights a notable increase in demand during the winter season. To effectively meet this surge in demand, the company should proactively prepare by ensuring an adequate supply of bikes, optimizing operational efficiency, and implementing strategic marketing efforts tailored to the unique characteristics of winter demand.

By incorporating these insights into their operational strategies, the company can enhance its responsiveness to market dynamics and optimize resource utilization, thereby improving overall customer satisfaction and business performance.



## Contact
Created by [@ArtificialIntelligence-Hub] - feel free to contact me!