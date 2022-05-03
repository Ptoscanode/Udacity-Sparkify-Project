# Udacity-Sparkify-Project

## Project Motivation
This project consists of appling Machine Learning models in Pyspark, to predict customer churn in a virtual company named "Sparkify". This company offers digital music service through streaming, similar to Spotify and Deezer. Sparkify has two account options: Free and Premium. The free account has advertisements between songs, whereas the premium account has no advertisements, costing a monthly fee. Customers can upgrade, downlgrade or cancel the service at any time. 

We will be working with a small dataset (128MB), containing information about customers and their activity in the platform. This project is divided in 5 parts:

1 - Load and Clean Dataset
2 - Exploratory Data Analysis
3 - Feature Engineering
4 - Modeling
5 - Conclusions

The reason why we will be working with a small fraction of the data is because this model is still being tested. Therefore, using a small dataset is way of, not only avoiding spending too long training the model, but also having a sense of the chosen model's accuracy before applying it to production data.


## Requirements
 - Access to a Spark Cluster to run this project or having java installed on your computer's system PATH , or the JAVA_HOME environment variable pointing to a Java installation. Spark runs on Java 8/11, Scala 2.12/2.13, Python 3.6+ and R 3.5+.

- The mini-dataset file `mini_sparkify_event_data.json`, a subset of the original data
- [Pyspark's SQL Module](https://spark.apache.org/docs/2.4.0/api/python/pyspark.sql.html)
- [Pyspark's Machine Learning package](https://spark.apache.org/docs/2.3.1/api/python/pyspark.ml.html)
- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [Matplotlib](http://matplotlib.org/)
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
