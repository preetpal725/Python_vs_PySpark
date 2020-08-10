# Python_vs_PySpark
You will see the basic data pre-processing differences between python and Pyspark coding

Please check my article on linkedin.com/in/preetpal725.
Dataset: https://archive.ics.uci.edu/ml/datasets/iris

I have written this article in collaboration with Himanshu Negi which will give you a kick start on how to use PySpark for basic data pre-processing 
for your machine learning algorithmns running on Spark clusters. By now most of you had hit the limitations of working with big data in Pandas (non-scalable)
and now exploring the journey of working with Spark dataframe (scalable). You can use pandas library for data pre-processing when the data is small 
but when you move to a larger (100 MB to multiple gigabytes) dataset the performance issue can make run-time much longer, and cause 
code to fail entirely because of the insufficient memory. This is where Spark comes into the picture for big data, we won’t go into Spark much but for 
starters Spark is a general-purpose distributed data processing engine and it can deal with large (100 gigabytes to multiple terabytes) datasets.

Previously working with small or medium size dataset, performance was not an issue while using Python, but as the data gets bigger day by day you have to catch 
up with the new technologies for working with big data for faster and parallel processing engines and that is where using PySpark is important. PySpark is 
basically a Python API to work with Spark.

Initially, while changing code from Python to PySpark you might have few questions like how much changes need to be made in order to convert the Python 
code to PySpark and if this question sounds familiar to you here is a Jupyter notebook (written in Databricks) showing the change in the syntax you will 
need to make while moving your code from Python to PySpark. 

The code is written in Databricks. You can use Databricks community edition and remember that it is free of cost.
