# Intro & Results
Sparkify is a fictitious music streaming app. As with most streaming services, users upgrade and downgrade service based on their experience and other personal factors. The goal of this project is to predict user downgrades with Machine Learning models which utilize user interaction with Sparkify.

On a smaller 128mb dataset, users who downgraded were predicted successfully at a rate of 95%. On a larger, 12gb dataset, users who downgraded were predicted successfully at a rate of 20%. Both prediciton sets had very low rates of false positive predictions (less than 1%).

## Full Discussion
A fuller discussion of results can be found at {blog address}


## Files
- *mini_sparkify_event_data.json* is the small dataset used for experimentation
- *Comparison.png* is the data visualization created with the small dataset
- *Sparkify.ipynb* is the jupyter notebook created on small dataset

## Libraries Used
- Findspark**
- Matplotlib*
- Pandas
- PySpark (http://spark.apache.org/docs/latest/api/python/index.html)

\*Matplotlib was only used on mini data set as AWS precludes use of Matplotlib in Jupyter
\*\*Findspark is Windows specific and helps with proper integration of PySpark with Jupyter


## Possible Improvements
The creator of this project has limited finances to use on AWS, so tuning and model tinkering were relatively limited. More financial expenditure could allow for more computing power and thus more extensive models and parameter grids to be tested.
