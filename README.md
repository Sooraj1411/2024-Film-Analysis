# **2024 Film Analysis**

## _Story Behind the Dashboard_
In the begining of 2024 what started as a casual habit turned out to be an Excel dashboard at the end of 2024. In the begining of 2024, I casually started noting the films that I watched in the google notes in my Phone along with the film's release year. Later at the end I saw there is good amount of films in it, around 150 films. So I got the curiosity to see some patterns in the data. The only problem was, I only had the Film's name and its release year, so first I load it in Excel and did some data cleaning like I used Text-To-Column feature and then used Power Query's feature Advance Editor and with the help of ChatGPT, I generated the code to fetch details of films through OMDB website (which is an open film database website). This is the first time I used API to fetch details from Internet. After the process, I did some data cleaning and made the dashboard.

## _Overview_
Analyzed the dataset that had 149 columns which had multiple columns like Movie name, Release Year, Director, IMDB rating, Rating, Box office, Release Date and many others. Handled Null Values and missing values, changed column types, used different visualisations to fetch interesting insights.

## _Insights_
+ Watched most films (17) released in 2024 year followed by 2023 (15) year and then 2017 (with 8 films).
+ Highest Runtime film which I watched - Animal(204 min), Oppenheimer(180 min)
+ 22 films that I watched were released in Oct month (most)
+ Deadpool 3 & Barbie contributed to most Revenue (28 % each of top 5) generating films.
+  Watched most films of Riddley Scott (4) whose overall IMDB rating is 7.8 while Christopher Nolan's film has highest IMDB rating of 8.6.
+  Watched R (49% of top 5) rated films mostly.
+  Top 5 rating (R, PG-13, Not Rated, N/A, PG) contributed to almost 92% of the total films watched.
+  Shawn Levy stands on top with 637 million box office collection with only 1 film (Deadpool 3) while Ridley Scott is at 4th with 431 million (despite she has 4 films in the data).
