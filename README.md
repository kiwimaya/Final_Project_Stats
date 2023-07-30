# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
- - Use the Citybikes API to Understand the number of bike stations in Fargo and their latitude and longitude
-  Identify if there is a shopping mall and restaurants around the bike stations using the YELP and Foursquare API
- Create a conclusion for this case with API provide better coverage of info


## Process
-	Try to understand how to make request from the API and get the information.
-	Format information into dataframes 
-	Compare info from both API’s and make a conclusion on which one provide better information.


## Results
-	Both API seems to define the name of their categories in different way that creates difference in the output of the query. Per example: 4Square when you query shopping mall the output is exact what match Shopping Mall vs YELP the out can bring other types of shopping locations not just Shopping Mall.

-	Another observation is about the size of the city and how it impacts the output. Per example for this project, the requested was to use a radius of less than 1 mile. Using that range there was almost no data in most of the stations. Due that I used a radius a higher radius.

-	Both Api’s seems to have limitation to make simple queries with multiple locations at the same time.

-	After reviewing the results of both Api’s I concluded the information from Foursquare is more accurate than the information from YELP. But I find YELP easier to use when you do not need too much accuracy on your search.


## Challenges 
Being so new to all the tools like API request, sql lite, statistic modeling, etc. made it very challenging to make useful and clear outcome with the information from the requests.

## Future Goals
Go back to these topics and really learn them once the bootcamp is done.
