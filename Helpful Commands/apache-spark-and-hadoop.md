### Helpful Commands for Apache Spark, Hadoop, & Oozie
* To list files in directory: `hadoop fs -ls {path}`
* To view contents of a file in hdfs: `hadoop fs -cat {path}`
* To check file space quota for prod DB: `hadoop fs -count -q -h -v {path to db}`
* To change permissions of file: `hdfs dfs -chmod -R 777 {path}`
* To check partitions for hdfs path: `hadoop fs -du -s -h`