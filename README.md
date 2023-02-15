## Introduction 🙋🏻‍♂️

AtliQ Grands owns multiple five-star hotels across India. They have been in the hospitality industry for the past 20 years. Due to strategic moves from other competitors and ineffective decision-making in management, AtliQ Grands are losing its market share and revenue in the luxury/business hotels category. As a strategic move, the managing director of AtliQ Grands wanted to incorporate “Business and Data Intelligence” to regain their market share and revenue. However, they do not have an in-house data analytics team to provide them with these insights.

Their revenue management team had decided to hire a 3rd party service provider to provide them with insights from their historical data.

## Task
- Create the metrics according to the metric list.
- Create a dashboard according to the mock-up provided by stakeholders.
- Create relevant insights that are not provided in the metric list/mock-up dashboard.

## Technology Stack 🔧
- Microsoft Power BI 📈

## Mock-up Dashboard
![Mockup Dashboard](https://github.com/devschow/Hospitality-Domain-Data-Analysis/blob/main/mock%20up%20dashboard_atliq%20grands.png?raw=true)

## Data Modeling:

![Data Model](https://github.com/devschow/Hospitality-Domain-Data-Analysis/blob/main/Data_model.jpg?raw=true)

TABLES CONNECTED

- fact_bookings > connected by “checkout_date” column;
- dim_date> connected by “date” column;
- dim_rooms > connected by “room_id” column;
- dim_hotels > connected by “property_id” column.
- fact_aggregated_bookings > connected by “property_id” column.

Measures created:

A total of 26 measures were created including:
- **Revenue**: To get the total revenue_realized.
- **ADR** (Average Daily Rate): It is the ratio of revenue to the total rooms booked/sold. It is the measure of the average paid for rooms sold in a given time period.
- **DSRN** (Daily Sellable Room Nights): This metrics tells on average how many rooms are ready to sell for a day considering a time period.


## Dashboard 🖼
- Dashboard 1:
![Dashboard 1](https://github.com/devschow/Hospitality-Domain-Data-Analysis/blob/main/Dashboard_1.jpg?raw=true)

- Dashboard 2:
![Dashboard 2](https://github.com/devschow/Hospitality-Domain-Data-Analysis/blob/main/Dashboard_2.jpg?raw=true)

## Key Insights
- AtliQ Exotica is the best performing property overall with highest ratings.
- Looking at weekly trend by metrics chart we can see that the weekly occupancy is fluctuating while the ADR remains nearly constant. This is an indicator that hotel chain is not using any dynamic pricing. 
- AtliQ  hotels have an opportunity to employ dynamic pricing in order to ramp up their revenue.
- A larger weekend occupancy (61.49%) presents an opportunity for the hotels to deploy weekday/weekend pricing. 
- AtliQ  Seasons, Mumbai is the overall worst performing hotel in the list. This is evident by looking at its Low average ratings, High cancellation rates.
- Hotel establishments in the luxury category bring in the most revenue (61.62%).   
- Mumbai generates the largest chunk of revenue (39.13%), followed by Bangalore (24.60%), Hyderabad (19.03%), and Delhi (17.23%).
- The greatest revenue share of almost 33% is held by Elite Rooms.
- With over 27k bookings, MakeYourTrip has been the most popular option for hotel booking.
- AtliQ hotels achieved an average rating of 3.62 over the past three months.

## 🔗 Let's Connect!
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/devarshi-choudhury-367aa11b0/)
