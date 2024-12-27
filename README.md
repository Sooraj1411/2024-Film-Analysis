# **2024 Film Analysis**

[Dashboard Link](https://github.com/Sooraj1411/2024-Film-Analysis/blob/main/Screenshot%202024-12-27%20183921.png)

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
+ Among the all films, 22 films were released in October (the most).

### _Film-Specific Highlights:_
+ Highest Runtime: Animal (204 min) and Oppenheimer (180 min).
+ Top Revenue Films: Deadpool 3 and Barbie contributed to 28% each of the top 5 revenue-generating films.
+ Director Highlights: Watched the most films by Ridley Scott (4), whose average IMDB rating is 7.8. However, Christopher Nolan's films have the highest average rating at 8.6.

### _Content and Ratings:_
+ Watched mostly R-rated films (49% of the top 5).
+ The top 5 ratings (R, PG-13, Not Rated, N/A, PG) made up 92% of the total films.

### _Box Office Insights:_
Shawn Levy leads with a box office collection of $637M (from Deadpool 3), while Ridley Scott collected $431M across 4 films.
