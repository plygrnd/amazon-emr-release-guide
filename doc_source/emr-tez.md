# Apache Tez<a name="emr-tez"></a>

Apache Tez is a framework for creating a complex directed acyclic graph \(DAG\) of tasks for processing data\. In some cases, it is used as an alternative to Hadoop MapReduce\. For example, Pig and Hive workflows can run using Hadoop MapReduce or they can use Tez as an execution engine\. For more information, see [https://tez\.apache\.org/](https://tez.apache.org/)\. Tez is included in Amazon EMR release version 4\.7\.0 and later\.

The following table lists the version of Tez included in the latest release of the Amazon EMR 6\.x series, along with the components that Amazon EMR installs with Tez\.

For the version of components installed with Tez in this release, see [Release 6\.5\.0 Component Versions](emr-650-release.md)\.


**Tez version information for emr\-6\.5\.0**  

| Amazon EMR Release Label | Tez Version | Components Installed With Tez | 
| --- | --- | --- | 
| emr\-6\.5\.0 | Tez 0\.9\.2 | emrfs, emr\-goodies, hadoop\-client, hadoop\-mapred, hadoop\-hdfs\-datanode, hadoop\-hdfs\-library, hadoop\-hdfs\-namenode, hadoop\-kms\-server, hadoop\-yarn\-nodemanager, hadoop\-yarn\-resourcemanager, hadoop\-yarn\-timeline\-server, tez\-on\-yarn | 

The following table lists the version of Tez included in the latest release of the Amazon EMR 5\.x series, along with the components that Amazon EMR installs with Tez\.

For the version of components installed with Tez in this release, see [Release 5\.34\.0 Component Versions](emr-5340-release.md)\.


**Tez version information for emr\-5\.34\.0**  

| Amazon EMR Release Label | Tez Version | Components Installed With Tez | 
| --- | --- | --- | 
| emr\-5\.34\.0 | Tez 0\.9\.2 | emrfs, emr\-goodies, hadoop\-client, hadoop\-mapred, hadoop\-hdfs\-datanode, hadoop\-hdfs\-library, hadoop\-hdfs\-namenode, hadoop\-kms\-server, hadoop\-yarn\-nodemanager, hadoop\-yarn\-resourcemanager, hadoop\-yarn\-timeline\-server, tez\-on\-yarn | 

**Topics**
+ [Creating a cluster with Tez](tez-create-cluster.md)
+ [Configuring Tez](tez-configure.md)
+ [Tez web UI](tez-web-ui.md)
+ [Timeline Server](tez-timeline-server.md)
+ [Tez release history](Tez-release-history.md)