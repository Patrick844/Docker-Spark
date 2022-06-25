# Machine-Learning-using-PySpark

Air Customer Satisfaction made using * Pyspark and Docker *

Air Customer Satisfaction Dataset : https://www.kaggle.com/datasets/sjleshrac/airlines-customer-satisfaction

## Installation

### Spark

Spark installation : https://spark.apache.org/downloads.html

### Docker

Docker installation : https://docs.docker.com/engine/install/

### Pyspark and jupyter notebook set up

Sign up to docker and pull this container : https://hub.docker.com/r/jupyter/pyspark-notebook

 ### Additional info

 For additional information on pyspark and jupyter on docker check these two links :

 - https://jupyter-docker-stacks.readthedocs.io/en/latest/index.html

 - https://spark.apache.org/docs/latest/api/python/

 ### Project

 After setting up everything, clone this repository and run it (Linux)
 
 sudo docker run -it -p 8888:8888 -v "${PWD}":/home/jovyan/work jupyter/pyspark-notebook 
 
 
