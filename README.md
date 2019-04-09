# Intro & Results
Sparkify is a fictitious music streaming app. As with most streaming services, users upgrade and downgrade service based on their experience and other personal factors. The goal of this project is to predict user downgrades with Machine Learning models which utilize user interaction with Sparkify.

On a smaller 128mb dataset, rows of users who would downgrade were predicted successfully at a rate of 95%. On a larger, 12gb dataset, rows of users who would downgrade were predicted successfully at a rate of 20%, up from an initial prediction rate of 5%. Both prediciton sets had very low rates of false positive predictions (less than .001%).

## Full Discussion
A fuller discussion of results can be found at https://medium.com/@ben.faus/predicting-customer-churn-using-spark-8772223150d3



## Files
- *mini_sparkify_event_data.json* is the small dataset used for experimentation
- *Comparison.png* is the data visualization created with the small dataset
- *Sparkify.ipynb* is the jupyter notebook created on small dataset
- *Sparkify.html* is the html version of the above notebook
- *FULL_Sparkify.ipynb* is the jupyter notebook created on the full 12gb dataset
- *FULL_Sparkify.html* is the html version of the above notebook

## Libraries Used
- Findspark**
- Matplotlib*
- Pandas
- PySpark (http://spark.apache.org/docs/latest/api/python/index.html)

\*Matplotlib was only used on mini data set as AWS precludes use of Matplotlib in Jupyter
\*\*Findspark is Windows specific and helps with proper integration of PySpark with Jupyter


## Conclusion & Possible Improvements
The final machine learning model successfully predicted 20% of the users in the 12gb data set who would downgrade their service in the next two weeks.

The creator of this project has limited finances to use on AWS, so tuning and model tinkering were relatively limited due to limited computing power. More financial expenditure could allow for more computing power and thus more extensive models and parameter grids to be tested.
