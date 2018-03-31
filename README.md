# Team

Mohammad Heidarian
Muhammed Taha Serdar
M.Hanny Sabbagh

# Topic

Our topic will be a study on TED talks. TED is a famous platform for innovative and creative people to spread their ideas. They publish their videos on their main website at TED.com which allows people from different parts of the world to view them.

We'll analyze the data regarding the published TED talks and try to answer some interesting questions (see below) relating to these talks, such as the relationships between its matrices and what insightful information can we extract of it.

# Data

Our data is consisting of TED talks metadata such as number of: Views, comments, shares.. and so on. We have a lot of other information available. The data source is mainly taken from: https://www.kaggle.com/rounakbanik/ted-talks, which includes TED talks data up to Sep 21, 2017.

The data is available on the form of a small CSV file which can be manipulated in many Python libraries such as Spark and Pandas. We'll use these two closely to run our project.

The nice thing about our data is that it's already clean and ready to use. There are ready columns for each specific metric we may need and generally it doesn't need any extra work of cleaning. This will help us to do our research quickly.

However, the data set includes only TED talks up to Sep 21, 2017. Which means that any published TED talk after this period is not included. This wouldn't affect our findings so much (since TED has been publishing talks for more than 10 years, so a period of few months is not that much), but it's worthy note to write down.

# Questions

In our research, we'll try to answer questions similar to:

- Is there a relationship between the number of views of a TED talk, and the duration of the video? Does the duration also affect other things such as number of comments?
- Is there a correlation between the above mentioned matrices (and others)? 
- In this case, does correlation imply causation? What are the results of running a hypothesis test?
- What are the most popular TED talks and their categories?
- Is rating of the TED talk affected by other things such as the category, duration, # of comments and others?

We'll depend on Pandas and Spark libraries in Python to run our project. We'll do operations such as matching columns, calculating correlation, finding a test statistic and so on. We'll also plot our results on graphs using Matplotlib.

# Conclusion

The aim of our project is to extract some insightful information from the raw date we have using Spark which we are learning in this course. These insights may be useful to understand how TED actually works and what attracts viewers attention and what does not. And as a speaker, what is a more important issue to focus on than the others.

This project is also helpful because it analyzes the data of an important project such as TED, which left an amazing change on the lives of many of us and many others around the world. The findings of our study could be interesting for any follower of TED, which are millions of people around the world.
