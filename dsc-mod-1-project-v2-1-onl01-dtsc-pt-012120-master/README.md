# Maximizing our profit in film industry


## Project Info

    My employer(Microsoft) decided to make a new movie studio without knowing anything about creating movies. They have hired me to help them understand the movie industry and related pros and cons. I am in charge of doing data analysis and presenting what type of movies are doing the best last 10 years.

### Goals
In this project the datasets from IMDb used to explore and understand what type of movies are doing the best in recent years. With provided data we can anser to following questions:
How many movies released each year?
Which month of the year is more profitable?
Which production budget is the most efficient for return of investment?
What is the runtime duration and genre of top rated movies and which genres are most profitable recently?
Which directors are making the most RoI?

### The Dataset
For this project some movie-related data was provided from :
IMDB
Rotten Tomatoes
TheMovieDB.org

### My Approach
Use pandas to initially ingest the datasets
Use pandas to clean columns, convert incorrect column types, add/drop columns, merge different dataframes.
Use seaborn to visualize data.


### Questions answered and their Recommendations


#### 1: How many movies released every year month?

We can see that number of released movies increased after 2009 and years 2013, 2014 and 2015 have the highest number of movies.
January and October are the highest in numbers.

##### Recommendation:
2013 through 2015 has the highest number of movies in the last 10 years
January, October are the top months movies releases happen.


#### 2. Which month of the year is more profitable to release a movie?

'tn_movie_budgets_gz' dataframe is used since it already has release dates and production budget, domestic gross, worldwide gross. Worldwide and Domestic ROI(return on investment) ratio calculated to show each movie's profitability by months. During grouping the ROI ratio by months, the mean () function is used to reach more accurate results.

##### Recommendation
June, July and August are the months with highest average both worldwide and domestic ROI,
top 4 months with highest average production budget are May, June, July and November,


#### 3. Which production budget ranges yield the most profitable movies?

##### Recommendation:

I found which budget films lead to profitable films most often. As the plot below show, the more you spend on a given film, the more likely it is to be profitable.


#### 4. Which genres are the most highly rated and most profitable recently?

##### Recommendation
We can see that  Action, Adventure, Comedy and Action, Adventure, Sci-Fi are doing the best both domestically and in general. Adventure, Animation, Comedy are the best among highly rated and profitable genres.

We can also see runtime minutes of the movies rated above 7.5. 
We can see that among highly rated movies Adventure, Animation and Comedy are the most profitable.
Most highly rated movies are from 100 to 130 minutes.


#### 5. Which directors are making the most profitable movies?
A director has a lot of impact on making a movie and is required to make decisions which will ultimately affect the profitability of a movie. Let's see which directors are doing the best and whom we should consider hiring.

##### Recommendation
Top 2 directors with the most profit are Travis Cluff and Chris Lofing





