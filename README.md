# Analyse Hacker News Posts Data With Basic Python and With Pandas
## Introduction 
Hacker News is a site started by the startup incubator Y Combinator, where user-submitted stories (known as "posts") are voted and commented upon, similar to reddit. Hacker News is extremely popular in technology and startup circles, and posts that make it to the top of Hacker News' listings can get hundreds of thousands of visitors as a result.

In this project, I used **basic Python** and **Pandas** to conduct analysis separately as a data science practice. In the analysis, I aim to determine: 

1. Do Ask HN or Show HN receive more comments on average?
2. Do posts created at a certain time receive more comments on average?
## The database
TThe data used for the analysis was accessed via https://www.kaggle.com/datasets/hacker-news/hacker-news-posts.

## Analysis using Basic Python
[Posting_in_Hacker_News_withBasicPython.ipynb](Posting_in_Hacker_News_withBasicPython.ipynb) used csv module to read the .csv data as a list of lists. Data filtering and counting were achieved with basic Python algorithms. The datetime module is used to transform string type date to datetime type for date-related analysis.  
 

## Analysis using Pandas
[Posting_in_Hacker_News_withPandas.ipynb](Posting_in_Hacker_News_withPandas.ipynb) used Pandas for the analysis.  


## Summary results 

Analysis of tabular data with basic Python and Pandas is demonstrated in this project. Pandas is a fast, flexible and easy to use as it is built on top of Python for tabular data mannipulation. 

The analysis results from the two approaches are consistent. Ask HN posts received more comments than the Show HN posts on average, indicating that Ask HN posts are more likely to receive comments. For Ask HN posts, creating a post at 15:00 Eastern Time in the US (which corresponds to UK time 20:00), has a higher chance of receiving comments.