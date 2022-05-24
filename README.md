# Flight-Cost-Analysis
Data Science, Machine Learning, and Predictive Models

Determining Optimal Times to Buy Airline Tickets for Domestic Flights within India

Dataset Source: https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction

Authors: Glenn Baevsky, Cindy Zhang, Parker English, Emily Robinson

Full Report found in Repository under Project_Final_Report.pdf

Abstract: 

Hundreds of millions of people take flights every year. These customers all pay for their trips, contributing greatly to the $470 billion airline industry. Domestic flights in India act as a good subset of data for this experiment, as the number of flights taken per year are a large enough sample size to be comparable to the worldscale population. Our team looks to provide individuals looking to fly domestically throughout India with the optimal times to purchase airline tickets to maximize their savings by answering three main questions, revolving around the variation of flight prices, optimal ticket prices for separate industries, and factors that increase airfare. To help answer these questions, we analyzed the vast array of data in our dataset, finding trends and patterns. After finding a commonality between airfare variation in subsequent days to flight departure, a linear regression prediction model confirmed that ticket price variation indeed had substantial correlation with what day the ticket was purchased before flight departure. We then found that ticket price in general was correlated with what day the ticket was purchased before flight departure.. To forecast ticket prices around the 20 to 50 day mark, we used the Holt Exponential Smoothing Forecast Model, which found all low range values. This recommendation report can conclude that the optimal time to buy tickets is between twenty and fifty days before the departure date, as ticket prices are significantly cheaper than they will be closer to the date, without much variation.

Introduction: 

With sanctions being imposed on the Russian economy, gas prices have soared. In the United States, these prices broke a new high since 2008. Soon, this rise in prices will reflect on the airline industry as airlines raise ticket prices to compensate for the new cost of fuel. The constant battle between airlines trying to make a profit and filling flight seats, causes ticket prices to drastically change. This complicates people’s abilities to determine when flight tickets are the most affordable. Since ticket prices fluctuate significantly over the course of the booking period, our goal is to help customers of domestic flights within India find the optimal time to purchase airline tickets. Even though our data constrains us to Indian domestic flights, we hope to find price patterns that can be applied to all flights around the world. Ultimately, these passengers will be able to use this information to make the best financial decisions when purchasing airline tickets.

Our team found this dataset on Kaggle, consisting of 300,155 records in total. Each record contains information on a single ticket for domestic Indian flights across six different airlines operating in this country. For each ticket we have information pertaining to the flight departure city and time, the flight arrival city and time, the class of the ticket, the duration of the flight, the price of the ticket, and the number of days between purchase of the ticket and flight departure.

