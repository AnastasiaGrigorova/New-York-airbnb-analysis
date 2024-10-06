# New-York-airbnb-analysis
The purpose of this project is to analyze the vacation rental market in the Manhattan Borough of New York City to determine the best types of properties for investment. Analysis is focused on vacation rentals, only rentals with a minimum night requirement of 7 days or fewer were applied.
The main metrics that were used to measure a high return rate are numbers of the of reviews for the last 12 months, types of neighborhoods, property size, occupancy rate, days of the week, whether the host is a super host or not, instant booking options, presence of doorman and correlation between a review scores and price.
The data for the research was used from the NYC Airbnb dataset, which consisted of listing information and a calendar.

The timeframe of analysis was for the last 12 months, focusing only on active users. Data was filtered according to the purpose of the research, analyzing variables that prove the financial success of an investment. Columns were filtered to address the need of the search. Pivot tables were used to quickly summarize large amounts of data and provide accurate findings.

To begin with, the number of days each property has been rented is an initial indicator of success. Reviews were used to estimate how frequently an Airbnb property is rented. It was assumed that reviews in the last 12 months are the best estimate of how often a listing is rented.

The analysis focused on finding the most attractive neighborhoods for vacation rentals based on the highest number of reviews during the last 12 months. Before identifying the top 10 neighborhoods, the data had been cleaned.

Here are the top 10 neighborhoods for investment:
1. Lower East Side
2. Hells Kitchen
3. Harlem
4. Midtown
5. Upper West Side
6. Chelsea
7. East Village
8. East Harlem
9. West Village
10. Nolita
The rest of the analysis was based on these findings, the top 10 neighborhoods for renting.

Property size was another factor to consider. It was determined that a 1-bedroom apartment is the optimal apartment size for a vacation rental, which received the highest number of average reviews accounting for 50,28%. The only exception is the neighborhood Midtown, where studio apartments got more reviews than in other New York boroughs.

The data also was aggregated to calculate the occupancy rate for each listing. This rate helped to identify the average annual revenue for an investment property.
To make that estimation these filters were applied:
- superhosts or properties with high review ratings;
- properties being very actively rented over the last 12 months;
- super luxury or extremely low-priced listings filtered out.

The average price and occupancy rate for a property were calculated to generate an estimate for annual revenue:
Price: $321.23
Occupancy Rate: 93.08%
Annual Revenue: 365 days * $321.23 * 93.08% = $109,131.98
As a result of this analysis, the Midtown neighborhood has the highest estimated annual revenue with an average of $109,131.98.

Additionally, it was determined which days of the week have the highest occupancy rates. By aggregating numeral valuables of days of the week and occupancy rate, Fridays proved to be the most popular days for renting.

Another feature that might positively impact how a property performs is if a host is a superhost. By analyzing the price of the property and occupancy rate, it appeared that even though superhosts have lower occupancy, their average annual revenue is approximately 30 % higher. The reason is the higher price that super hosts charge for their properties.

An attribute of offering instant booking didn’t prove to make a drastic difference. By comparing listings with or without an instant booking option, it turned out that the difference in the occupancy rate is only 0.63%, which makes it an insufficient feature to use.

"Another finding showed that buildings with doormen get better review scores for check-in and, therefore, can attract more clients. However, the difference isn’t significant either and should be considered as an optional benefit. 
"

An additional feature that can positively impact the profit of rents is that hosts can charge higher prices if their properties have higher review ratings. After analyzing the average of review scores and an average of price, the correlation between rating and profit was obvious. Thereby, the average revenue of properties that scored rating ‘5’ is $372.43, compared to $276.39 that scored only ‘4.5’. It shows a significant difference of 35%.

To summarise, investing in one-bedroom apartments in the Midtown in the Manhattan borough of New York City will be the best solution for the business. Implementing the findings from this analysis will give the investor an additional benefit to make the most of their investment.
