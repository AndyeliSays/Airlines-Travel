--- SQL CLEANING & ANALYSIS -> [ Airlines_travel_SQL.md ](https://github.com/AndyeliSays/Airlines/blob/main/Airlines_travel_SQL.md)

--- TABLEAU DASHBOARD ->

<img src=https://github.com/AndyeliSays/Airlines_travel/blob/main/Airline_travel_assets/airline_travel_tableau.png>

<h1 align="center">Airline Travel </h1>

## Introduction:
  
The goal of this analysis is to transform raw airline, travel, and revenue data into actionable findings that can help airlines make data-driven decisions. This process aims to uncover opportunities for improving operational efficiency, optimizing revenue, and enhancing the passenger experience.

The dataset consists of several tables (8) which include aircrafts_data, airports_data, boarding_passes, bookings, flights, seat, ticket_flights, tickets.

<img src=https://github.com/AndyeliSays/Airlines_travel/blob/main/Airline_travel_assets/airlinetables.png width="1200">

## Business Task & Objectives: 
  
This project will leverage SQL for data extraction, transformation, and analysis. Key metrics such as flight delays, ticket sales per booking, and aircraft utilization will be explored to provide a comprehensive understanding of airline operations. By the end of this project, we aim to deliver a clear summary of findings that can contribute to improving operational efficiency, enhancing customer satisfaction, and identifying areas for revenue optimization within the airline industry.

Some examples of questions, topics addressed but not limited to:
- Which airports are the most visited and what is their revenue? by Month? by Flight?
- How many passengers travel per booking?
- Which routes experience the most delays?
- Which aircraft models are most frequently used?
- What booking class is the most popular?
- Ticket volume and Ticket Sales in Monthly Overview
- Occupancy Rate

## Tools:
- Data cleaning, preparation, analysis done in SQL.
- Data visualizations made in Tableau.

## Data Source: 
[Airlines Dataset 1](https://www.kaggle.com/datasets/mohammadkaiftahir/airline-dataset/data)
[Airlines Dataset 2](https://www.kaggle.com/datasets/saadharoon27/airlines-dataset/data)

---

<h1 align="center">Insights </h1>

## Operational Scale and Revenue
- Total revenue generated is approximately $20.77 billion from 33,121 flights.
- The airline served 262,788 bookings, suggesting an efficient booking-to-flight ratio.
- Average revenue per flight appears to be around $627,000 indicating a profitable operation.

## Fleet Performance
- Airbus A321-200 is a significant contributor with 107,129 flights.
- Boeing models (777-300, 767-300, 737-300) collectively account for a substantial portion of operations.
- Regional aircraft like Bombardier CRJ-200 (150,122 flights) and Sukhoi Superjet-100 play important roles in the network.

## Temporal Patterns
- Weekday distribution shows highest traffic on Fridays (141,574 flights) and Sundays (153,136 flights).
- Morning hours (9-11 AM) see peak traffic, with 11 AM having the highest number of flights (106,563).
- Late night/early morning (1-3 AM) shows minimal activity, as expected.
- Timeline chart shows seasonal variations with peaks around late July and early September.

## Airport & Geographic Operations
- Sheremetyevo International Airport dominates with 99,300 operations. Domodedovo International Airport follows closely with 97,441 operations.
- Map shows a concetration of airports in western Russia with key regional hubs including smaller airports serving as regional connection points.
- East to west connectivity appears stronger than north to south routes.

## Passenger Behavior
- Most bookings (173,397) are for single tickets.
- Multi-ticket bookings decrease significantly as the number increases.
- Business class generates substantial revenue, especially for long-haul aircrafts.

## Recommendations
- The airline should optimize scheduling for the most profitable time slots (9-11 AM).
- Airlines should consider the strong performance of Airbus A321-200 and Bombardier CRJ-200.
- Revenue optimization could focus on Friday and Sunday operations.
- Airport operations at Sheremetyevo and Domodedovo and Pulkovo may benefit from efficiency improvements to reduce delays.
