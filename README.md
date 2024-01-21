# Big data engineering(BDE) notebook
## Tools of BDE: Introduction and Installation on win 11
### System Requirements
- Windows 11
- AMD Ryzen 6800
### Installation of Spark (Prerequisites for PySpark)
Pyspark is a python lib to invoke the Spark on your computer/vm. Hence, before installing PySpark, ensure that the following dependencies are installed:
- Java 17 LTS (JDK 17 LTS) is recommened (Java 21 LTS is NOT suit for spark 3.5 or 3.5-)
- Scala (generally:Spark 3.+ match scala 2.12.X/2.13.X)
- Spark
- Hadoop (Optional) Win need winutils 
> **Note**: PySpark requires Python version 3.8 or later, and for R users, R version 3.5 or later is needed.
### Path setting of Java, Scala, and Spark
Once you have set the env use [win + R] to check the installation
spark-shell
### Additional Resources
- [Java 17 LTS NOT Java 21](<https://www.oracle.com/java/technologies/downloads/#java17>)
- [Link to version match check between Spark&Scala](<https://mvnrepository.com/artifact/org.apache.spark/spark-core>)
- [Spark Second latest version is better](<https://spark.apache.org/downloads.html>)
- [Hadoop is optional](<https://github.com/cdarlint/winutils>)
  
### Using PySpark on Windows
- [Guide for PySpark installation on Windows](<link-to-windows-setup>)
- 
      # Creat a python environment for pyspark
      conda create -n pyspark_env python=3.9
      # activate new env (or conda activate pyspark_env)
      activate pyspark_env


### Using PySpark on Google Colab
colab is strong and ready for running the Pyspark and spark SQL
- [Instructions on setting up PySpark on Google Colab](<link-to-colab-setup>)

## Tools of BDE: Introduction and Installation on linux server
### Linux sever setting
### System Requirements
- 
- 
    # linux server set of Pyspark
      # installations:
      # 
      # Virtual server for Pyspark
      # linux sys version
      # cmd code
  # demo of BDE flow on Pyspark
    # basic function of Pyspark-read
    # basic function/definition of RDD
    # functions list
  # BDE in defferent area
    # Finance
