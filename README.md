# IMDb Web Scraping and Interactive Dashboard

## Overview

This project involves web scraping the IMDb website to extract information about the top 1000 movies, including details such as title, release year, rating, genre, runtime, director, cast, and votes. The data was then transformed and cleaned to create a structured dataset. This dataset was used to create an interactive dashboard using Tableau, which provides valuable insights into the world of cinema.

## Dashboard Preview

Here is a glimpse of what the Tableau dashboard looks like:

![Dashboard Preview](https://github.com/sriramm04/IMDB_Webscrape_using_python_and_Tableau/assets/129077845/3a89727c-4111-4ee5-86cd-659110f1dddd)

## Access the Interactive Dashboard

You can explore the interactive version of this IMDb movie analysis by visiting the following link: [IMDb Interactive Dashboard](https://public.tableau.com/app/profile/sriram.v4931/viz/ImdbWebScrapeDashboard/Dashboard1).

## Data Collection

To collect data from IMDb, Python libraries such as BeautifulSoup and requests were used. The data was extracted from multiple pages, ensuring that a comprehensive list of top-rated movies was obtained. The collected data was stored in a dictionary and later converted into a pandas DataFrame for further analysis.

## Data Cleaning and Transformation

The data underwent several cleaning and transformation steps:

- The "Votes" column was cleaned to remove commas and converted to an integer data type.
- The "Release year" column was formatted to display only the year, and its data type was changed to datetime.
- The "Genre" column was cleaned to remove unnecessary newline characters.

## Insights from the Dashboard

The Tableau dashboard provides several interactive visualizations:

1. **Film Makers by Movie Rating**: Explore the top directors based on the average rating of their movies within the top 1000 list. Hover over each director to view additional details such as their total number of movies and the highest-rated movie they directed.

2. **Top Movies by Rating**: Get a glimpse of the highest-rated movies in IMDb's top 1000 list. Hover over each movie to see details like its release year, director, and genre. Discover the cinematic masterpieces that have garnered the highest viewer ratings.

3. **Movies by Votes**: Understand which movies have received the most votes from IMDb enthusiasts. Hover over each movie to access information about its release year, director, and genre. Discover the films that have captured the attention and engagement of the audience.

4. **Genre by Movie Counts**: Uncover the most prevalent movie genres among the top-rated films. Hover over each genre to see the number of movies in that category and the percentage it represents. Identify which genres dominate the list and are favored by IMDb enthusiasts.

5. **Movies by Release Year**: Explore the distribution of movies by their release years. Hover over each year to view the total number of movies released in that year and their cumulative ratings. Gain insights into how IMDb's top 1000 list spans various decades and eras of filmmaking.


## Access the Interactive Dashboard

You can explore the interactive version of this IMDb movie analysis by visiting the following link: [IMDb Interactive Dashboard]([your_tableau_dashboard_link_here](https://public.tableau.com/app/profile/sriram.v4931/viz/ImdbWebScrapeDashboard/Dashboard1)).

Feel free to dive into the dashboard to gain deeper insights into the top-rated movies on IMDb, and use the tooltips to access additional information. Enjoy your journey through the world of cinema!

For any questions or further information, please contact sriramvenky004@gmail.com.
