# **2024 Film Analysis**

## _Story Behind the Dashboard_
At the beginning of 2024, what started as a casual habit turned into an insightful Excel dashboard by the year's end. I began casually noting down the films I watched along with their release years in Google Notes on my phone. By the end of the year, I had accumulated a dataset of around 150 films.
<br>
Curious to uncover patterns, I decided to analyze the data. However, I only had the film names and their release years. To enrich the dataset, I loaded it into Excel and used Power Query's Advanced Editor. With the help of ChatGPT, I generated code to fetch additional details (e.g., runtime, IMDB ratings, box office collection, etc.) using the OMDB API—marking my first experience with APIs. After cleaning and transforming the data, I built an interactive dashboard to visualize my 2024 movie-watching journey.

## _Overview_
The dataset contained 149 rows and multiple columns such as:

+ Movie Name
+ Release Year
+ Director
+ IMDB Rating
+ Box Office Revenue
+ Release Date
+ Content Rating

## _Key Steps_
+ Data Enrichment: Fetched movie details using the OMDB API.
+ Data Cleaning: Handled null and missing values, changed column types, and transformed data for analysis.
+ Visualization: Designed an interactive dashboard to showcase insights and patterns.

## _Insights_

### _General Trends:_
+ Watched the most films (17) released in 2024, followed by 15 films from 2023 and 8 films from 2017.
+ October was the most popular month, with 22 films watched.

### _Film-Specific Highlights:_
+ Highest Runtime: Animal (204 min) and Oppenheimer (180 min).
+ Top Revenue Films: Deadpool 3 and Barbie contributed to 28% each of the top 5 revenue-generating films.
+ Director Highlights: Watched the most films by Ridley Scott (4), whose average IMDB rating is 7.8. However, Christopher Nolan's films have the highest average rating at 8.6.

### _Content and Ratings:_
+ Watched mostly R-rated films (49% of the top 5).
+ The top 5 ratings (R, PG-13, Not Rated, N/A, PG) made up 92% of the total films.

### _Box Office Insights:_
Shawn Levy leads with a box office collection of $637M (from Deadpool 3), while Ridley Scott collected $431M across 4 films.

+ Watched most films (17) released in 2024 year followed by 2023 (15) year and then 2017 (with 8 films).
+ Highest Runtime film which I watched - Animal(204 min), Oppenheimer(180 min)
+ 22 films that I watched were released in Oct month (most)
+ Deadpool 3 & Barbie contributed to most Revenue (28 % each of top 5) generating films.
+  Watched most films of Riddley Scott (4) whose overall IMDB rating is 7.8 while Christopher Nolan's film has highest IMDB rating of 8.6.
+  Watched R (49% of top 5) rated films mostly.
+  Top 5 rating (R, PG-13, Not Rated, N/A, PG) contributed to almost 92% of the total films watched.
+  Shawn Levy stands on top with 637 million box office collection with only 1 film (Deadpool 3) while Ridley Scott is at 4th with 431 million (despite she has 4 films in the data).
