# Netflix-EDA

## Overview

Netflix is one of the most popular media and video streaming platforms. They have over 10000 movies or # tv shows available on their platform, as of mid-2021, they have over 222M Subscribers globally. This tabular dataset consists of listings of all the movies and tv shows available on Netflix, along with details such as - cast, directors, ratings, release year, duration, etc.

This Python script analyzes Netflix data using the Pandas, Matplotlib, Seaborn, and WordCloud libraries. The dataset used in this analysis contains information about Netflix shows and movies, including details such as title, genre, cast, release date, and more.

**The analysis covers various aspects of the dataset, including data cleaning, exploratory data analysis, and data visualization. It provides insights into the distribution of content, ratings, genres, countries, and other factors within the Netflix library.**

## Prerequisites

Before running the code, ensure you have the following libraries installed:
- Pandas
- NumPy
- Matplotlib
- Seaborn
- WordCloud

You can install these libraries using pip:

pip install pandas numpy matplotlib seaborn wordcloud

## Usage
1. Download the Netflix dataset (netflix.csv) and place it in the same directory as the Python script.

2. Open the Python script in a suitable environment (e.g., Jupyter Notebook or any Python IDE).

3. Run the script. It will load and analyze the Netflix data, generating various visualizations and insights.

4. Explore the generated plots and insights to gain a better understanding of the Netflix dataset.

## Files
netflix.csv: The dataset containing Netflix show and movie information.
Netflix_Data_Analysis.ipynb: The Python script for data analysis.

## Understanding the Dataset

The dataset has a list of all the TV shows/movies available on Netflix:
**Show_id**: Unique ID for every Movie / Tv Show
**Type**: Identifier - A Movie or TV Show
**Title**: Title of the Movie / Tv Show
**Director**: Director of the Movie
**Cast**: Actors involved in the movie/show
**Country**: Country where the movie/show was produced
**Date_added**: Date it was added on Netflix
**Release_year**: Actual Release year of the movie/show
**Rating**: Maturity Rating of the movie/show
**Duration**: Total Duration - in minutes or number of seasons
**Listed_in**: Genre
**Description**: The summary description

## Results
The analysis provides insights into the Netflix dataset, including:

1. Distribution of movies vs. TV shows.
2. Content distribution across countries.
3. Top directors, actors, and genres.
4. Average duration of movies and seasons of TV shows.
5. Content added over the years, months, and weekdays.
