# Visualization-Using-d3.js

Objective
The visual will show the daily deal industry in a quick yet intuitive manner. The main plots for the visualization here are :-
Online review/rating correlation to deal success
Deal category frequency


Methodology
To do this, dataset called visualdata.csv was used along with a wide range of technologies: MongoDB for storing and querying the data, Python for building a web server that interacts with the Database and serving html pages, Javascript library d3.js for building interactive charts. 

Steps:-
1. Getting and understanding the data :- Getting the insights of the data.
2. Storing and querying the data :- Getting a subset of the dataset for plotting. Here I've used only some of the columns from the dataset like yelp_category, yelp_reviews, yelp_rating, revenue, num_sold. For this, installed mongodb and pymongo, then filtered and grouped the data using the mongo shell.
3. Front-end side preparation :- Install virtualen and Flask and used python for building a web server using flask and then rendering a html page from the python code. ex- app.py 
4. Building the charts :- I am using Stacked Bar Chart using d3.js library for the visualization and the code for the same is encapsulated into our main file called index.html. This html file imports data from the csv file and uses d3.js library to plot the data into the chart.

Visualization
Have built a visual that represents the success of daily deals according to the category and also the impact of online reviews and rating on the number of deals sold and accordingly on the revenues. It can be clearly concluded from the visual that more the number of online reviews/rating ,more is the number of deals sold and vice versa. Also we can see the frequency of each deal category in terms of deals sold/ revenue and accordingly we can improve the deals for the categories that hold less revenue.  








