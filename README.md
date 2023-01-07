# Project-1
Movie Ratings Analysis using Python

Analyzing the rating given by viewers of a movie helps many people decide whether or not to watch that movie.
Finding the distribution of the ratings of all the movies given by the viewers.
Picking the top 10 movies that got 10 ratings by viewers.

Necessary Python Libraries:Numpy,Pandas,Plotly

First loaded the Movies dataset,it dont have any column names,so defined column names "ID","Title","Genre".Then loaded the RAtings dataset even this dataset dont have column names,so defined column names "User","ID","Ratings","Timestamp".Then i have merged both the datasets based on the common column name "ID".Then plotted pie chart using plotly to see the distribution of the ratings of all the movies given by the viewers.So, according to the pie chart most movies are rated 8 by users.it can be said that most of the movies are rated positively.

As 10 is the highest rating a viewer can give,picked the top 10 movies that got 10 ratings by viewers by using Python Qurey() method.
