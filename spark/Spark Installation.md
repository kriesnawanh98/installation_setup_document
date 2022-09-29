# Spark Installation

This documentation is provided for helping someone who wants to install Apache Spark data processing framework especially in local computer.

Overall, Installing Apache Spark is separated in 4 different stages as follows:

1. Installing and verifying a Java Installation
2. Installing Spark
3. Adding a winutils file
4. Setup an environment variable

1. **Installing and verifying a Java Installation**

The java version which suitable with the spark framework is only JAVA SE 8 8u202, so make sure that the installed java has an appropriate version.

Download a java JDK .exe file from the following link:

[https://www.oracle.com/java/technologies/javase/javase8-archive-downloads.html](https://www.oracle.com/java/technologies/javase/javase8-archive-downloads.html)

![Untitled](Spark%20Installation/Untitled.png)

note: the java installation must be provide the JDK format not only JRE file.

The installed java should be stored probably in “**C:\Program Files\Java**”

![Untitled](Spark%20Installation/Untitled%201.png)

1. **Installing Spark**

In this tutorial, The spark version used is 2.4.8 with hadoop 2.7 

Download a spark file from the following link:

[https://archive.apache.org/dist/spark/spark-2.4.8/](https://archive.apache.org/dist/spark/spark-2.4.8/)

![Untitled](Spark%20Installation/Untitled%202.png)

after downloaded the .tgz file, the file should be moved and extracted in a specific path.

for instance, **C:\spark-2.4.8-bin-hadoop2.7\**

![Untitled](Spark%20Installation/Untitled%203.png)

1. **Adding a winutils/hadoop file**

Considering winutils version, Download a specific winutils file which suitable with version of Hadoop. 

the provided link contains some winutils file for each hadoop version

[https://github.com/steveloughran/winutils](https://github.com/steveloughran/winutils)

Download and extract the folder of winutils

![Untitled](Spark%20Installation/Untitled%204.png)

path: **C:\hadoop-2.7.1**

1. **Setup an environment variable**

At the end, Each path of saved folder have to be stored in the System Properties - Environment Variable in a local computer. The stored variable is separated into 2 section such as “User Variable for user” and “System Variables”

4.1 User Variable for User

1. adding HADOOP_HOME, JAVA_HOME and SPARK_HOME variable
    
    ![Untitled.png](Spark%20Installation/Untitled%205.png)
    

1. adding bin folder of JAVA, SPARK and hadoop in Path variable
    
    ![Untitled (1).png](Spark%20Installation/Untitled_(1).png)
    

4.2 System Variables

1. adding HADOOP_HOME and JAVA_HOME variable
    
    ![Untitled (1).png](Spark%20Installation/Untitled_(1)%201.png)
    

1. adding PYSPARK_PYTHON and SPARK_HOME  variable
    
    ![Untitled.png](Spark%20Installation/Untitled%206.png)
    

1. adding bin folder of JAVA, SPARK and hadoop  in Path variable

![Untitled (4).png](Spark%20Installation/Untitled_(4).png)