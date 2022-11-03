# Big-Data-module-project-


## Configuration of a Hadoop Cluster

Apache Hadoop and Apache Spark are both open-source Frameworks for processing big data with a few key differences.  Hadoop uses MapReduce to process data, while Spark uses resilient distributed datasets (RDD). Hadoop has a distributed file system (HDFS), which means that data files can be stored on multiple machines.
The file system is scalable, as servers and machines can be added to accommodate growing volumes of data. Spark does not provide a distributed file storage system, so it is primarily used for computation.
The good news is that Spark is fully compatible with Hadoop and works seamlessly with Hadoop Distributed File System (HDFS). Thus, when the size of the data is too large for Spark to manage in for Spark to handle it in memory, Hadoop can help overcome this obstacle with its HDFS functionality.

![image](https://user-images.githubusercontent.com/66222519/199700123-c08bd133-c8c7-4509-b92f-824ce5374c0f.png)
