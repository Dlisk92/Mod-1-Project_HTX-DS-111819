# Module 1 Project

Project has a README file clearly documenting data understanding, project goals, and findings.

## The Project

Microsoft sees all the other big companies creating original video content, and they want to get in on the fun. They have decided to create a new movie studio, but the problem is they don’t know anything about movies. They have hired us, flatironDS, to help them better understand the movie industry.

FlatironDS is expected to:
        - Do data analysis and create a presentation that explores what type of films are currently doing the best at the box office. 
        - Translate those findings into actionable insights that the CEO can use when deciding what type of films they should be creating.


## Methodology 

Some of the areas that were examined were movie genres, revenue and budget to answer questions such as:
    - what genres made the most money?
    - What movie genres required the most investment?
    - What type of movies most companies were investing?
    - Which genres were more likely to give profit?
 

## Data Sources

The data was obtained by making API requests on [TheMovieDB.org](https://www.themoviedb.org/?language=en-US). We started with almost 6000 movies and after cleaning we had about 144 movies in our dataset. We also dropped some 
We only analyzed movie data from 2018. For data cleaning, we dropped all rows with null values, zero revenue/budget because they would not be relevant for the analysis. We also dropped any moveis that had budgets of $10,000 or less because it didn't seem that the data was very accurate and it could have a negative impact on our analysis.


## Results

 - Action, adventure and animation are the top three genres that generate most profit.
 - Distribution shows that most of the movies were action, drama and comedy.
 - Risk analysis shows that investing in Animation, family, history and romance moveis is less risky.
 
 
 ## Recommendation
 We recommend going for animation movies because they are in the group of movies that generate the most profit and they also have low risk of not being profitable.
 


