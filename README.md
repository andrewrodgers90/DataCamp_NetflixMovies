This is the first project on the "Data Analyst with Python" career track on DataCamp.
Below is the background information, data, and task given in the project.

**BACKGROUND INFORMATION**

Netflix! What started in 1997 as a DVD rental service has since exploded into one of the largest entertainment and media companies.

Given the large number of movies and series available on the platform, it is a perfect opportunity to flex your exploratory data analysis skills and dive into the entertainment industry. 
Our friend has also been brushing up on their Python skills and has taken a first crack at a CSV file containing Netflix data. 
They believe that the average duration of movies has been declining. 
Using your friends initial research, you'll delve into the Netflix data to see if you can determine whether movie lengths are actually getting shorter and explain some of the contributing factors, if any.

You have been supplied with the dataset netflix_data.csv , along with the following table detailing the column names and descriptions:

**The data**

CSV file: netflix_data.csv
Column:	Description
show_id:	The ID of the show
type:	Type of show
title:	Title of the show
director:	Director of the show
cast:	Cast of the show
country:	Country of origin
date_added:	Date added to Netflix
release_year:	Year of Netflix release
duration:	Duration of the show in minutes
description:	Description of the show
genre:	Show genre

**PROJECT INSTRUCTIONS**

Your friend suspects that movies are getting shorter and they've found some initial evidence of this. 
Having peaked your interest, you will perform exploratory data analysis on the netflix_data.csv data to understand what may be contributing to movies getting shorter over time. 
Your analysis will follow these steps:

Load the CSV file and store as netflix_df.
Filter the data to remove TV shows and store as netflix_subset.
Investigate the Netflix movie data, keeping only the columns "title", "country", "genre", "release_year", "duration", and saving this into a new DataFrame called netflix_movies.
Filter netflix_movies to find the movies that are strictly shorter than 60 minutes, saving the resulting DataFrame as short_movies; inspect the result to find possible contributing factors.
Using a for loop and if/elif statements, iterate through the rows of netflix_movies and assign colors of your choice to four genre groups ("Children", "Documentaries", "Stand-Up", and "Other" for everything else). Save the results in a colors list. Initialize a matplotlib figure object called fig and create a scatter plot for movie duration by release year using the colors list to color the points and using the labels "Release year" for the x-axis, "Duration (min)" for the y-axis, and the title "Movie Duration by Year of Release".
After inspecting the plot, answer the question "Are we certain that movies are getting shorter?" by assigning either "yes" or "no" to the variable answer.
Click the "Submit Project" button to check your solution.
