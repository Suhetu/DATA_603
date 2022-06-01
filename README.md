## -----DATA603 Final Project: Online Grocery Recommender System-----

### Credits:

	Sravya Pamula(DP51938)
	Mohan Brahma Harsha Vanga(HI77773)
	Suhetu Ring(SS13214)

### Data Source:

https://www.kaggle.com/yasserh/instacart-online-grocery-basket-analysis-dataset

### Data Size:

1.28 GB on MongoDB

### Total Data Size:

3.6+ GB with merged spark dataframes

The following dependencies need to be set up in order for the project to run:
1. MongoDB on a local standalone cluster setup
2. PySpark
3. Python 3.6+


Versions of above dependencies used for this project are:

MongoDB: 1.31.2

PySpark: 3.2.1

Python: 3.6.8


Following are the steps to setup a MongoDB standalone cluster:

https://www.geeksforgeeks.org/install-mongodb-compass-on-windows/


Following are the steps to install PySpark:

https://changhsinlee.com/install-pyspark-windows-jupyter/


*The Jupyter notebook has to be in the same directory as the 5 csv files which can be downloaded from data source mentioned above*


Open the Jupyter Notebook using command prompt or Anaconda.

### Steps to run the Project as shown in the Jupyter Notebook (in chronological order):

1. Import libraries
2. Import data csv files using pandas
3. Push those csv files into MongoDB (localhost) as collections with the help of MongoClient
4. Setup and configure a spark environment using PySpark
5. Retrieve the big data from MongoDB as Spark Dataframes using MongoClient
6. Perform data wrangling using Spark (ex- merging and dropping of dataframe)
7. Perform EDA using Spark and Python
8. Calculate ratings for products by each user as shown
9. Apply Machine Learning, Collaborative Filtering (a recommender system technique) to the Spark DataFrame using Spark MLlib.
10. Generate recommendations for users
11. Generate visualizations on Tableau and build dashboard

## -------------------------------------------------------------------------------
