# About problems i solved

## hadoop
### about : hadoop-native lib - with hadoop2.7.x
> `cd $HADOOP_HOME/lib/native`

> `cp ./* ../` # copy to lib/

## hive
### about : $SPARK_HOME/lib/spark-assembly-*.jar - with spark2.x
> `cd $HIVE_HOME/bin`

> `vim hive` # hive.sh

> replace '${SPARK_HOME}/lib/spark-assembly-*.jar' with '${SPARK_HOME}/jars/*.jar'

## spark
