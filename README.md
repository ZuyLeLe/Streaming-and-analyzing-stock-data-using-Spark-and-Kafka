# Streaming-and-analyzing-stock-data-using-Spark-and-Kafka
Fetch real-time stock data from yahoo finance then stream and analyze the data uing Spark and Kafka
## Running instructions
First, run this code in these commands in 2 seperated terminal (command prompt):
```
pyspark
```
```
spark-shell
```
Then, cd to the kafka folder and rung the following codes in seperated terminal as well:
```
bin\windows\zookeeper-server-start config\zookeeper.properties
```
```
bin\windows\kafka-server-start config\server.properties
```
Lastly, cd to the repo clone and run ```
pip install requirements.txt
```
