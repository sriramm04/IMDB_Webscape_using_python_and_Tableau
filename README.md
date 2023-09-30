# IMDb Web Scraping and Interactive Dashboard

## Overview

This project involves web scraping the IMDb website to extract information about the top 1000 movies, including details such as title, release year, rating, genre, runtime, director, cast, and votes. The data was then transformed and cleaned to create a structured dataset. This dataset was used to create an interactive dashboard using Tableau, which provides valuable insights into the world of cinema.

## Dashboard Preview

Here is a glimpse of what the Tableau dashboard looks like:

![Dashboard Preview](![Dashboard 1](https://github.com/sriramm04/IMDB_Webscrape_using_python_and_Tableau/assets/129077845/c270dc08-0d9b-4125-a516-68551cd73aaf)
)

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

1. **Top Film Makers by Total Number of Movies**: This bar chart displays the top directors based on the total number of movies in the top 1000 list. It allows users to explore the most prolific directors in IMDb's top-rated movies.

2. **Top Film Makers by Ratings of Movies**: This bar chart showcases directors based on the cumulative ratings of their movies in the top 1000 list. Users can identify directors whose movies have received the highest ratings.

3. **Movies by Year and Total Ratings**: This line chart illustrates the distribution of movies by release year and their total ratings. It helps users understand how the IMDb ratings have evolved over the years.

4. **Top 10 Movie Genres**: A pie chart highlights the top 10 movie genres based on their frequency in the top 1000 list. Users can see which genres are the most popular among top-rated movies.

## Access the Interactive Dashboard

You can explore the interactive version of this IMDb movie analysis by visiting the following link: [IMDb Interactive Dashboard]([your_tableau_dashboard_link_here](https://public.tableau.com/app/profile/sriram.v4931/viz/ImdbWebScrapeDashboard/Dashboard1)).

Feel free to explore the dashboard to gain deeper insights into the top-rated movies on IMDb. Enjoy your journey through the world of cinema!

For any questions or further information, please contact sriramvenky004@gmail.com.
