This notebook looks at 2 datasets of movie budgets and title details to provide reccomendations for hypothetical movie executives from Microsoft interested in opening a movie studio and compete in the movie industry. 
The following sections outline the process taken that lead to a concluding analysis and recommendation. 
The notebook takes a time series approach to observe yearly and monthly trends to guage popular release times and genres and uses gross profit as an indicator for consumer interest throughout the analysis. 

1. Changing data type of monetary values to compute for total profit 

2. Joining 'imdb.title.basics.csv' dataset with 'tn.movie_budgets.csv' dataset

3. Changing data type of 'Release Date' to reflect datetime

4. Creating new df to start analysis on seasonality

5. Grouping for last 10 years

6. Chart each seasonal gross profit trend for past decade

7. Gross profit by Winter, Spring, Summer, and Fall for past decade

8. Starting 1 year genre analysis between 2017 and 2018

9. Monthly Gross Profit trend between 2017 and 2018

10. Monthly gross profit trend as a mean for past 10 years for comparison 

11. Genre/Theme analysis