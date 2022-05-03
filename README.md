# Udacity-Sparkify-Project

## Project Motivation



This is the final project of the datascience nanodegree (DSND). We have an example of a virtual company called 'Sparkify' who offers paid and free listening service, the customers can switch between either service, and they can cancel their subscription at any time. The given customers dataset is huge (12GB), thus the standard tools for analysis and machine learning will not be useful here as it will not fit in the computer's memory (even the data can fit in the memory of a 32GB computer, the analysis, and computations require way more than that amount, and the analysis will crash the system). The safe way to perform such analysis is to do it using Big Data tools like Apache Spark which is one of the fastest big data tools.

Sparkify is a digital music service similar to Netease Cloud Music or QQ Music. Many of the users stream their favorite songs in Sparkify service everyday, either using free tier that places advertisements in between the songs, or using the premium subscription model where they stream music as free, but pay a monthly flat rate. User can upgrade, downgrade or cancel their service at anytime.

For this tutorial, we worked with only a 128MB slice of the original dataset.

This project consists of analyzing disaster data from Figure Eight to build a model for an API that classifies disaster messages.

We used a data set containing real messages that were sent during disaster events. Then, a machine learning pipeline was created to categorize these events so that we can send the messages to an appropriate disaster relief agency.

This project also includes a web app where an emergency worker can input a new message and get classification results in several categories. The web app also displays visualizations of the data

In this project, our goal is handling a customer churn problem by building predictive model on a small dataset (~125MB) of customer's activities on the service and attempt to predict customers who will churn based on their past behaviours.


## Requirements
 - Access to a Spark Cluster to run this project
 - The mini-dataset file `mini_sparkify_event_data.json`, a subset of the original data
 - [Pyspark's SQL Module](https://spark.apache.org/docs/2.4.0/api/python/pyspark.sql.html)
- [Pyspark's Machine Learning package](https://spark.apache.org/docs/2.3.1/api/python/pyspark.ml.html)
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [Seaborn](https://seaborn.pydata.org/)
- [Python's Regular Expressions module](https://docs.python.org/3/library/re.html)
- [Python's datetime module](https://docs.python.org/3/library/datetime.html)


## Files in the Repository
`Toscano_Paulo_Sparkify.ipynb`: Jupyter notebook containing the analysis of the project

`Toscano_Paulo_Sparkify.ipynb`: The HTML version of the Jupyter notebook

***Obs:***
The mini-dataset file `mini_sparkify_event_data.json`, used for this project is available only at [Udacity](www.udacity.com)


## Results

The project summary can be found on [Medium](https://medium.com/)


## Acknowledgements

https://github.com/othneildrew/Best-README-Template/blob/master/README.md

https://sparkbyexamples.com/pyspark/pyspark-add-new-column-to-dataframe

https://sparkbyexamples.com/pyspark/pyspark-dataframe-groupby-and-sort-by-descending-order

https://sparkbyexamples.com/pyspark/pyspark-join-explained-with-examples/

https://sparkbyexamples.com/pyspark/pyspark-concatenate-columns/
 
https://sparkbyexamples.com/pyspark/pyspark-sql-date-and-timestamp-functions/
 
https://sparkbyexamples.com/pyspark/pyspark-udf-user-defined-function/

https://www.geeksforgeeks.org/merge-two-dataframes-in-pyspark/

https://www.geeksforgeeks.org/concatenate-two-pyspark-dataframes/
 
https://www.datasciencemadesimple.com/join-in-pyspark-merge-inner-outer-right-left-join-in-pyspark/
