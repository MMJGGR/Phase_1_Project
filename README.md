# Microsoft Enters the Movie Business:

### Author: Richard Macharia

### Project Overview

This project aims to guide Microsoft's entry into the movie business by leveraging data analysis to uncover insights into the factors driving film success. By exploring trends in genres, ratings, popularity, budget, and profitability, we aim to equip Microsoft with actionable recommendations for creating a thriving movie studio.

### Business Problem

Microsoft, a technology giant, is venturing into the film industry with a new movie studio. However, they lack experience in film production and need guidance on:

* What types of films are currently performing well?
* What factors contribute to a movie's success?
* What budget and marketing strategies should be employed?


### Data Sources

This analysis leverages two primary datasets:

1. **TMDB Movies:** This dataset provides information on movie popularity, ratings, release dates, budgets, and revenue.
2. **IMDB Data (via SQLite database):** This database includes tables with details about movies, cast and crew, genres, and ratings.

### Analysis Approach

We will employ a combination of data cleaning, exploratory data analysis (EDA), and visualization techniques to:

* Clean and integrate the data from different sources.
* Explore the distribution of genres, ratings, and production budgets.
* Analyze the relationship between budget, popularity, ratings, and profitability.
* Identify the most successful genres and key factors contributing to movie success.
* Provide actionable recommendations to guide Microsoft's movie studio strategy.

### Key Questions

The following questions will guide our analysis:

1. What are the most popular and critically acclaimed movie genres?
2. How does production budget affect a movie's profitability and critical reception?
3. What is the relationship between a movie's popularity, rating, and profitability?
4. Who are the most successful directors and other key professionals in the industry?
5. What actionable recommendations can be derived from the data to guide Microsoft's movie studio launch? 


### Summary and Findings

**Genre:**

Drama is the most frequently produced genre, indicating its widespread appeal to filmmakers and studios. It also receives the highest total rating (weighted by numvotes), confirming its popularity among audiences.
Action, Adventure, Comedy, and Thriller genres also hold strong positions in both frequency and total rating, showcasing the diverse preferences of audiences and filmmakers.
Genres like Animation and Fantasy, while still within the top 10 by total rating, exhibit a smaller share of the total votes, potentially due to their more specific appeal.

![alt text](image.png)

**Ratings and Popularity:**

There is a moderate positive correlation between movie ratings and popularity (number of votes). Popular films tend to be rated more.
The total rating metric, which incorporates both averagerating and numvotes, highlights the importance of popularity in determining a movie's overall success. Highly popular films can achieve higher total ratings even with slightly lower average ratings.
A movie's high rating doesn't guarantee financial success, but it can play a significant role in combination with popularity.

![alt text](image-1.png)

**Budget and Profitability:**

High budgets do not necessarily guarantee critical or commercial success. Many lower-budget films can be profitable and popular with audiences.
Popularity is a stronger predictor of profitability than ratings alone.
There is no one singular path to a movie's success, both high and low production budgets can be popular with audiences resulting in their profitability.

![alt text](image-2.png)

**Professionals and the Industry:**

Directors are the most common primary profession, underscoring their importance in filmmaking but many professionals in the industry also have multiple roles
Filmmakers and audiences may have differing preferences, as indicated by the discrepancy between most produced genres (Drama, Documentary) and highest-rated genres (Drama, Action).

![alt text](image-3.png)

**Overall:**

+ The film industry is diverse with no single formula for success.
+ Popularity is a crucial driver of financial success, but ratings and what filmmakers bring to the table still hold value.
+ Understanding the target audience and implementing effective marketing strategies to make movies more popular are essential for filmmakers.
+ The data suggests that success is achievable for both big-budget blockbusters and smaller, well-crafted films.
+ The industry runs on collaboration between diverse professionals with various skill sets.



## Directory Hierarchy
```
|—— .gitignore
|    |—— im.db
|—— data
|    |—— im.db
|    |—— tmdb.movies.csv
|    |—— tn.movie_budgets.csv
|—— index.ipynb
|—— presentation.pdf
```
