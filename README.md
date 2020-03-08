

Scenario -- Microsoft sees all the big companies creating original video content, and they want to get in on the fun. They have decided to create a new movie studio, but the problem is they don’t know anything about creating movies. The aim of the project is to help them better understand the movie industry.

This notebook explores what type of films are currently doing the best at the box office. The slide deck translates the findings from the jupyter notebook into actionable insights that the CEO can use when deciding what type of films they should be creating.

The following sections outline the data analysis used for the concluding analysis and final recommendation. The data analysis performed in the notebook takes a time series approach to observe yearly and monthly trends to guage popular release times and genres and uses gross profit as an indicator for consumer interest. 

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
