# Hadoop

hive table structure  partition/bucket/cluster


WebHCat
wasb[s]://%HADOOP_HOME%/conf/core-site.xml
adl://mydatalakestore/<cluster_root_path>/

The core-site.xml file contains information such as the port number used for Hadoop instance, memory allocated for the file system, memory limit for storing the data, and the size of Read/Write buffers.
The hdfs-site.xml file contains information such as the value of replication data, the namenode path, and the datanode path of your local file systems. It means the place where you want to store the Hadoop infra.

