# Market-basket-analysis-using-hive
Here we are performing real time market basket analysis using hive on dynamic updating data

** THIS DIRECTORY HAS CODE WITH AND WITHOUT HIVE AND HAS DATASET ** 

There are 2 files 
1. one is using hive where you have to store data in to hive which is a data warehousing software which uses a sql like query to store update data.
2. another is without the use of hive that is importing the dtaset simply using pandas.

for storing data into hive i have used hortonworks docker sandbox HDP inside a virtual machine to store dataset in to hive which is a big data component used for real time storage and analysis of data you can use any other techniques also.

#algorthms used for market basket analysis
1. association rule mining
2. apriori algorithm

#required libraries for using hive in jupyter notebook
1. pandas
2. numpy
3. matplotlib
4. squarify
5. seaborn
6. mlxtend-for association rule mining and apriori algorithm
7. networkx-for drawing network diagram o frequent items

**NOTE To use jupyter notebook with hive you need additional libraries with above libraries
1. thrift_sasl 
2. pyhive-for hive module
3. impala-for having connectivity to hive 
