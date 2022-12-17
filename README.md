# 1 Spark ML

- With the increase in data sizes and various sources of data, solving machine learning problems using standard techniques pose a big challenge 
- Spark is a distributed processing engine using the MapReduce framework to solve problems related to big data and processing of it
    
# 2 Pyspark
PySpark is an interface for Apache Spark in Python. It not only allows you to write Spark applications using Python APIs, but also provides the PySpark shell for interactively analyzing your data in a distributed environment.

# 3 Machine Learning

- Machine learning (ML) is the study of computer algorithms that can improve automatically through experience and by the use of data

# 4 Need Of Spark ML
- When data is huge we need to use spark MLlib

# 5 Types of Learning
- Supervised Learning
- UnSupervised Learning

# 6 Data Pre-Processing

- Data preprocessing is a process of preparing the raw data and making it suitable for a machine learning model

# 7 Classification Algorithms 
- Decision Tree Classification 
- Random Forest Classification

# 8 Clustering Algorithms 
- K-Means Clustering  



# 9 Business Overview Of Airlines Industry

- https://openflights.org/
- https://developer.ibm.com/exchanges/data/all/airline/  
- https://www.bts.dot.gov/topics/airlines-and-airports/quick-links-popular-air-carrier-statistics  

# 10 S3 link for dataset

- s3://airlines555/airline/data  


# 11 Code Description
    File Name : DecisionTree.ipynb, RandomForest.ipynb,   
                K_means.ipynb ,  
                DecisionTree.py, RandomForest.py   
                and K_means.py  
    DataSets : data.zip, Social_Network_Ads.csv  
    File Description : Implement Spark MLlib algorithms  
    
## Steps to Run
There are two ways to execute the end to end flow.  
- Command Prompt => python script  
- spark_path spark-submit file_path  
- spark_path => <path_to_spark>>  
- file_path => <path_to_file>   
- Data file path is same as script file path  

eg. <C:\Users\admin\Desktop\spark\bin>spark-submit C:\Users\admin\Desktop\sparkml\DecisionTree.py>  


- IPython  

### Modular code
- Create virtualenv  
- Install requirements `pip install -r requirements.txt`  
- Run Code `python DecisionTree.py`  
- Check output for all the visualization  
### IPython  
Follow the instructions in the notebook `DecisionTree.ipynb`  
