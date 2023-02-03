This code performs an analysis on movie ratings data from IMDb, with a focus on the top 10 rated movies and summary statistics for average ratings. The code uses the Pandas library to load and manipulate the data, Numpy to set the X-axis ticks on the bar chart, and Matplotlib to plot the bar chart.

How to use the code
Call the movie_ratings_analysis function and provide a minimum number of votes as an argument. This will filter out movies with fewer than the specified number of votes.
The function will load the movie ratings data from IMDb and store it in a Pandas DataFrame.
The function will then group the movies by average rating and count the number of movies in each group.
A bar chart will be plotted to show the top 10 rated movies. The X-axis will show the average ratings and the Y-axis will show the number of movies.
Summary statistics for the average ratings will be calculated and displayed, including the mean, median, and standard deviation.
Example
python
Copy code
movie_ratings_analysis(25000)
This call to the function will perform the analysis on movies with at least 25,000 votes. The resulting bar chart will show the top 10 rated movies with 25,000 votes or more and the summary statistics will show the mean, median, and standard deviation of the average ratings for these movies.
