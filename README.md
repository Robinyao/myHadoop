# myHadoop
A Hadoop platform to study.

## Version
- Hadoop : 2.7.3
- Hive : 1.2.1
- Spark : 2.0.0

## exports
- Ubuntu : **`~/.bashrc`**

> ```
export JAVA_HOME=/usr/lib/jvm/java-8-openjdk-amd64
export HADOOP_HOME=/home/myHadoop/hadoop-2.7.3
export HADOOP_COMMON_LIB_NATIVE_DIR=$HADOOP_HOME/lib/native
export HADOOP_OPTS="-Djava.library.path=$HADOOP_HOME/lib"
export HIVE_HOME=/home/myHadoop/hive-1.2.1
export SPARK_HOME=/home/myHadoop/spark-2.0.0
export PYTHONPATH=$SPARK_HOME/python/:$SPARK_HOME/python/lib/py4j-0.10.1-src.zip:$PYTHONPATH
export CLASSPATH=.:$CLASSPATH:$JAVA_HOME/lib:$HADOOP_HOME/myclass:$HIVE_HOME/lib:$SPARK_HOME/lib
export PATH=$PATH:$JAVA_HOME/bin:$HADOOP_HOME/bin:$HIVE_HOME/bin:$SPARK_HOME/bin
```

## data/
### These are sogou user query logs

- sogou1.txt 100K records
- sogou2.txt 300K records

