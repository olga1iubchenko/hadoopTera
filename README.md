# hadoopTera
This is a project for the assignment of CSC 550 Big Data. 

## 1. Quick Start
### 1. How to build
```
cd hadoopTera/hadoop-mapreduce-examples 
mvn package
```
### 2. How to run
```
hadoop jar target/hadoop-mapreduce-examples-3.2.0.jar teragen -Dmapred.map.tasks=10 100 inputTest
hadoop jar target/hadoop-mapreduce-examples-3.2.0.jar terasort input10GB output10GB
hadoop jar target/hadoop-mapreduce-examples-3.2.0.jar teravalidate output10GB validate10GB
```
### 2. Workspace 
Our work direction is under `hadoop-mapreduce-examples/src/main/java/org/apache/hadoop/examples/terasort`.

