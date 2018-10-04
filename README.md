# TMDb
Project Background
This is a data analysis project that I completed for a Udacity Data Analyst Nanodegree. In this project I analyze a movie dataset using Pandas, NumPy, Matplotlib and descriptive statistics to answer questions that I was interested in researching. Since the use of inferential statistics or machine learning was beyound the scope of this project, my conclusions should be viewed as tentative.

Dataset Background
I downloaded the data set file (tmdb-movies.csv) from this Undacity Google Drive. Undacity completed some data wrangling from the original data on Kaggle. This data set contains information about 10,000 movies collected from The Movie Database (TMDb), including user ratings and revenue.

Certain columns, like ‘cast’ and ‘genres’, contain multiple values separated by pipe (|) characters. The final two columns ending with “_adj” show the budget and revenue of the associated movie in terms of 2010 dollars, accounting for inflation over time. According to the overview section on Kaggle (currated the data) it is not clear if the budgets and revenues are all in US dollars and if they consistently show the global revenues.

One other piece of advice from Kaggle is that it is probably a good idea to treat values of zero in the budget field as missing, with the caveat that missing budgets are much more likely to have been from small budget films in the first place.

Dataset Questions
After reviewing the available fields I decided to focus on the following questions that I felt could be answered by this data set:

What are the profit trends of movies over time?
What are the characteristics of movies with high revenue?
