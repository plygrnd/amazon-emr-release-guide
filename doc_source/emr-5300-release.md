# Amazon EMR release 5\.30\.0<a name="emr-5300-release"></a>
+ [Application versions](#emr-5300-app-versions)
+ [Release notes](#emr-5300-relnotes)
+ [Component versions](#emr-5300-components)
+ [Configuration classifications](#emr-5300-class)

## Application versions<a name="emr-5300-app-versions"></a>

The following applications are supported in this release: [https://flink.apache.org/](https://flink.apache.org/), [http://ganglia.info](http://ganglia.info), [http://hbase.apache.org/](http://hbase.apache.org/), [https://cwiki.apache.org/confluence/display/Hive/HCatalog](https://cwiki.apache.org/confluence/display/Hive/HCatalog), [http://hadoop.apache.org/docs/current/](http://hadoop.apache.org/docs/current/), [http://hive.apache.org/](http://hive.apache.org/), [https://hudi.apache.org](https://hudi.apache.org), [http://gethue.com/](http://gethue.com/), [https://jupyterhub.readthedocs.io/en/latest/#](https://jupyterhub.readthedocs.io/en/latest/#), [https://livy.incubator.apache.org/](https://livy.incubator.apache.org/), [https://mxnet.incubator.apache.org/](https://mxnet.incubator.apache.org/), [http://mahout.apache.org/](http://mahout.apache.org/), [http://oozie.apache.org/](http://oozie.apache.org/), [https://phoenix.apache.org/](https://phoenix.apache.org/), [http://pig.apache.org/](http://pig.apache.org/), [https://prestodb.io/](https://prestodb.io/), [https://spark.apache.org/docs/latest/](https://spark.apache.org/docs/latest/), [http://sqoop.apache.org/](http://sqoop.apache.org/), [https://www.tensorflow.org/](https://www.tensorflow.org/), [https://tez.apache.org/](https://tez.apache.org/), [https://zeppelin.incubator.apache.org/](https://zeppelin.incubator.apache.org/), and [https://zookeeper.apache.org](https://zookeeper.apache.org)\.

The table below lists the application versions available in this release of Amazon EMR and the application versions in the preceding three Amazon EMR releases \(when applicable\)\.

For a comprehensive history of application versions for each release of Amazon EMR, see the following topics:
+ [Application versions in Amazon EMR 6\.x releases](emr-release-app-versions-6.x.md)
+ [Application versions in Amazon EMR 5\.x releases](emr-release-app-versions-5.x.md)
+ [Application versions in Amazon EMR 4\.x releases](emr-release-app-versions-4.x.md)


**Application version information**  

|  | emr\-5\.30\.0 | emr\-5\.29\.0 | emr\-5\.28\.1 | emr\-5\.28\.0 | 
| --- | --- | --- | --- | --- | 
| AWS SDK for Java | 1\.11\.759 | 1\.11\.682 | 1\.11\.659 | 1\.11\.659 | 
| Flink | 1\.10\.0 | 1\.9\.1 | 1\.9\.0 | 1\.9\.0 | 
| Ganglia | 3\.7\.2 | 3\.7\.2 | 3\.7\.2 | 3\.7\.2 | 
| HBase | 1\.4\.13 | 1\.4\.10 | 1\.4\.10 | 1\.4\.10 | 
| HCatalog | 2\.3\.6 | 2\.3\.6 | 2\.3\.6 | 2\.3\.6 | 
| Hadoop | 2\.8\.5 | 2\.8\.5 | 2\.8\.5 | 2\.8\.5 | 
| Hive | 2\.3\.6 | 2\.3\.6 | 2\.3\.6 | 2\.3\.6 | 
| Hudi | 0\.5\.2\-incubating | 0\.5\.0\-incubating | 0\.5\.0\-incubating | 0\.5\.0\-incubating | 
| Hue | 4\.6\.0 | 4\.4\.0 | 4\.4\.0 | 4\.4\.0 | 
| JupyterEnterpriseGateway |  \-  |  \-  |  \-  |  \-  | 
| JupyterHub | 1\.1\.0 | 1\.0\.0 | 1\.0\.0 | 1\.0\.0 | 
| Livy | 0\.7\.0 | 0\.6\.0 | 0\.6\.0 | 0\.6\.0 | 
| MXNet | 1\.5\.1 | 1\.5\.1 | 1\.5\.1 | 1\.5\.1 | 
| Mahout | 0\.13\.0 | 0\.13\.0 | 0\.13\.0 | 0\.13\.0 | 
| Oozie | 5\.2\.0 | 5\.1\.0 | 5\.1\.0 | 5\.1\.0 | 
| Phoenix | 4\.14\.3 | 4\.14\.3 | 4\.14\.3 | 4\.14\.3 | 
| Pig | 0\.17\.0 | 0\.17\.0 | 0\.17\.0 | 0\.17\.0 | 
| Presto | 0\.232 | 0\.227 | 0\.227 | 0\.227 | 
| PrestoSQL |  \-  |  \-  |  \-  |  \-  | 
| Spark | 2\.4\.5 | 2\.4\.4 | 2\.4\.4 | 2\.4\.4 | 
| Sqoop | 1\.4\.7 | 1\.4\.7 | 1\.4\.7 | 1\.4\.7 | 
| TensorFlow | 1\.14\.0 | 1\.14\.0 | 1\.14\.0 | 1\.14\.0 | 
| Tez | 0\.9\.2 | 0\.9\.2 | 0\.9\.2 | 0\.9\.2 | 
| Trino |  \-  |  \-  |  \-  |  \-  | 
| Zeppelin | 0\.8\.2 | 0\.8\.2 | 0\.8\.2 | 0\.8\.2 | 
| ZooKeeper | 3\.4\.14 | 3\.4\.14 | 3\.4\.14 | 3\.4\.14 | 

## Release notes<a name="emr-5300-relnotes"></a>

The following release notes include information for Amazon EMR release version 5\.30\.0\. Changes are relative to 5\.29\.0\.

Initial release date: May 13, 2020

Last updated date: June 25, 2020

**Upgrades**
+ Upgraded AWS SDK for Java to version 1\.11\.759
+ Upgraded Amazon SageMaker Spark SDK to version 1\.3\.0
+ Upgraded EMR Record Server to version 1\.6\.0
+ Upgraded Flink to version 1\.10\.0
+ Upgraded Ganglia to version 3\.7\.2
+ Upgraded HBase to version 1\.4\.13
+ Upgraded Hudi to version 0\.5\.2\-incubating
+ Upgraded Hue to version 4\.6\.0
+ Upgraded JupyterHub to version 1\.1\.0
+ Upgraded Livy to version 0\.7\.0\-incubating
+ Upgraded Oozie to version 5\.2\.0
+ Upgraded Presto to version 0\.232
+ Upgraded Spark to version 2\.4\.5
+ Upgraded Connectors and drivers: Amazon Glue Connector 1\.12\.0; Amazon Kinesis Connector 3\.5\.0; EMR DynamoDB Connector 4\.14\.0

**New features**
+ **EMR Notebooks** – When used with EMR clusters created using 5\.30\.0, EMR notebook kernels run on cluster\. This improves notebook performance and allows you to install and customize kernels\. You can also install Python libraries on the cluster master node\. For more information, see [Installing and Using Kernels and Libraries](https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-managed-notebooks-installing-libraries-and-kernels.html) in the *EMR Management Guide*\.
+ **Managed Scaling** – With Amazon EMR version 5\.30\.0 and later, you can enable EMR managed scaling to automatically increase or decrease the number of instances or units in your cluster based on workload\. EMR continuously evaluates cluster metrics to make scaling decisions that optimize your clusters for cost and speed\. For more information, see [Scaling Cluster Resources](https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-scale-on-demand.html) in the *Amazon EMR Management Guide*\.
+ **Encrypt log files stored in Amazon S3** – With Amazon EMR version 5\.30\.0 and later, you can encrypt log files stored in Amazon S3 with an AWS KMS customer managed key\. For more information, see [Encrypt log files stored in Amazon S3](https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-plan-debugging.html#emr-log-encryption) in the *Amazon EMR Management Guide*\.
+ **Amazon Linux 2 support** – In EMR version 5\.30\.0 and later, EMR usesAmazon Linux 2 OS\. New custom AMIs \(Amazon Machine Image\) must be based on theAmazon Linux 2 AMI\. For more information, see [Using a Custom AMI](https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-custom-ami.html)\.
+ **Presto Graceful Auto Scale** – EMR clusters using 5\.30\.0 can be set with an auto scaling timeout period that gives Presto tasks time to finish running before their node is decommissioned\. For more information, see [Using Presto automatic scaling with Graceful Decommission](presto-graceful-autoscale.md)\.
+ **Fleet Instance creation with new allocation strategy option** – A new allocation strategy option is available in EMR version 5\.12\.1 and later\. It offers faster cluster provisioning, more accurate spot allocation, and less spot instance interruption\. Updates to non\-default EMR service roles are required\. See [Configure Instance Fleets](https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-instance-fleet.html)\.
+ **sudo systemctl stop and sudo systemctl start commands** – In EMR version 5\.30\.0 and later, which useAmazon Linux 2 OS, EMR uses `sudo systemctl stop` and `sudo systemctl start` commands to restart services\. For more information, see [How do I restart a service in Amazon EMR?](https://aws.amazon.com/premiumsupport/knowledge-center/restart-service-emr/)\.

**Changes, enhancements, and resolved issues**
+ EMR version 5\.30\.0 doesn't install Ganglia by default\. You can explicitly select Ganglia to install when you create a cluster\.
+ Spark performance optimizations\.
+ Presto performance optimizations\.
+ Python 3 is the default for Amazon EMR version 5\.30\.0 and later\.
+ The default managed security group for service access in private subnets has been updated with new rules\. If you use a custom security group for service access, you must include the same rules as the default managed security group\. For more information, see [Amazon EMR\-Managed Security Group for Service Access \(Private Subnets\)](https://docs.aws.amazon.com/emr/latest/ManagementGuide/emr-man-sec-groups.html#emr-sg-elasticmapreduce-sa-private)\. If you use a custom service role for Amazon EMR, you must grant permission to `ec2:describeSecurityGroups` so that EMR can validate if the security groups are correctly created\. If you use the `EMR_DefaultRole`, this permission is already included in the default managed policy\.

**Known issues**
+ **Lower "Max open files" limit on older AL2\.** Amazon EMR releases: emr\-5\.30\.x, emr\-5\.31\.0, emr\-5\.32\.0, emr\-6\.0\.0, emr\-6\.1\.0, and emr\-6\.2\.0 are based on older versions ofAmazon Linux 2 \(AL2\), which have a lower ulimit setting for "Max open files" when EMR clusters are created with the default AMI\. The lower open file limit causes a "Too many open files" error when submitting Spark job\. In the impacted EMR releases, the Amazon EMR default AMI has a default ulimit setting of 4096 for "Max open files," which is lower than the 65536 file limit in the latestAmazon Linux 2 AMI\. The lower ulimit setting for "Max open files" causes Spark job failure when the Spark driver and executor try to open more than 4096 files\. To fix the issue, Amazon EMR has a bootstrap action \(BA\) script that adjusts the ulimit setting at cluster creation\. Amazon EMR releases 6\.3\.0 and 5\.33\.0 will include a permanent fix with a higher "Max open files" setting\.

  The following workaround for this issue lets you to explicitly set the instance\-controller ulimit to a maximum of 65536 files\.

**Explicitly set a ulimit from the command line**

  1. Edit `/etc/systemd/system/instance-controller.service` to add the following parameters to Service section\.

     `LimitNOFILE=65536`

     `LimitNPROC=65536`

  1. Restart InstanceController

     `$ sudo systemctl daemon-reload`

     `$ sudo systemctl restart instance-controller`

  **Set a ulimit using bootstrap action \(BA\)**

  You can also use a bootstrap action \(BA\) script to configure the instance\-controller ulimit to 65536 files at cluster creation\.

  ```
  #!/bin/bash
  for user in hadoop spark hive; do
  sudo tee /etc/security/limits.d/$user.conf << EOF
  $user - nofile 65536
  $user - nproc 65536
  EOF
  done
  for proc in instancecontroller logpusher; do
  sudo mkdir -p /etc/systemd/system/$proc.service.d/
  sudo tee /etc/systemd/system/$proc.service.d/override.conf << EOF
  [Service]
  LimitNOFILE=65536
  LimitNPROC=65536
  EOF
  pid=$(pgrep -f aws157.$proc.Main)
  sudo prlimit --pid $pid --nofile=65535:65535 --nproc=65535:65535
  done
  sudo systemctl daemon-reload
  ```
+ **Managed scaling**

  Managed scaling operations on 5\.30\.0 and 5\.30\.1 clusters without Presto installed may cause application failures or cause a uniform instance group or instance fleet to stay in the `ARRESTED` state, particularly when a scale down operation is followed quickly by a scale up operation\.

  As a workaround, choose Presto as an application to install when you create a cluster, even if your job does not require Presto\.
+ Known issue in clusters with multiple master nodes and Kerberos authentication

  If you run clusters with multiple master nodes and Kerberos authentication in EMR releases 5\.20\.0 and later, you may encounter problems with cluster operations such as scale down or step submission, after the cluster has been running for some time\. The time period depends on the Kerberos ticket validity period that you defined\. The scale\-down problem impacts both automatic scale\-down and explicit scale down requests that you submitted\. Additional cluster operations can also be impacted\. 

  Workaround:
  + SSH as `hadoop` user to the lead master node of the EMR cluster with multiple master nodes\.
  +  Run the following command to renew Kerberos ticket for `hadoop` user\. 

    ```
    kinit -kt <keytab_file> <principal>
    ```

    Typically, the keytab file is located at `/etc/hadoop.keytab` and the principal is in the form of `hadoop/<hostname>@<REALM>`\.
**Note**  
This workaround will be effective for the time period the Kerberos ticket is valid\. This duration is 10 hours by default, but can configured by your Kerberos settings\. You must re\-run the above command once the Kerberos ticket expires\.
+ The default database engine for Hue 4\.6\.0 is SQLite, which causes issues when you try to use Hue with an external database\. To fix this, set `engine` in your `hue-ini` configuration classification to `mysql`\. This issue has been fixed in Amazon EMR version 5\.30\.1\.

## Component versions<a name="emr-5300-components"></a>

The components that Amazon EMR installs with this release are listed below\. Some are installed as part of big\-data application packages\. Others are unique to Amazon EMR and installed for system processes and features\. These typically start with `emr` or `aws`\. Big\-data application packages in the most recent Amazon EMR release are usually the latest version found in the community\. We make community releases available in Amazon EMR as quickly as possible\.

Some components in Amazon EMR differ from community versions\. These components have a version label in the form `CommunityVersion-amzn-EmrVersion`\. The `EmrVersion` starts at 0\. For example, if open source community component named `myapp-component` with version 2\.2 has been modified three times for inclusion in different Amazon EMR release versions, its release version is listed as `2.2-amzn-2`\.


| Component | Version | Description | 
| --- | --- | --- | 
| aws\-sagemaker\-spark\-sdk | 1\.3\.0 | Amazon SageMaker Spark SDK | 
| emr\-ddb | 4\.14\.0 | Amazon DynamoDB connector for Hadoop ecosystem applications\. | 
| emr\-goodies | 2\.13\.0 | Extra convenience libraries for the Hadoop ecosystem\. | 
| emr\-kinesis | 3\.5\.0 | Amazon Kinesis connector for Hadoop ecosystem applications\. | 
| emr\-notebook\-env | 1\.0\.0 | Conda env for emr notebook | 
| emr\-s3\-dist\-cp | 2\.14\.0 | Distributed copy application optimized for Amazon S3\. | 
| emr\-s3\-select | 1\.5\.0 | EMR S3Select Connector | 
| emrfs | 2\.40\.0 | Amazon S3 connector for Hadoop ecosystem applications\. | 
| flink\-client | 1\.10\.0 | Apache Flink command line client scripts and applications\. | 
| ganglia\-monitor | 3\.7\.2 | Embedded Ganglia agent for Hadoop ecosystem applications along with the Ganglia monitoring agent\. | 
| ganglia\-metadata\-collector | 3\.7\.2 | Ganglia metadata collector for aggregating metrics from Ganglia monitoring agents\. | 
| ganglia\-web | 3\.7\.1 | Web application for viewing metrics collected by the Ganglia metadata collector\. | 
| hadoop\-client | 2\.8\.5\-amzn\-6 | Hadoop command\-line clients such as 'hdfs', 'hadoop', or 'yarn'\. | 
| hadoop\-hdfs\-datanode | 2\.8\.5\-amzn\-6 | HDFS node\-level service for storing blocks\. | 
| hadoop\-hdfs\-library | 2\.8\.5\-amzn\-6 | HDFS command\-line client and library | 
| hadoop\-hdfs\-namenode | 2\.8\.5\-amzn\-6 | HDFS service for tracking file names and block locations\. | 
| hadoop\-hdfs\-journalnode | 2\.8\.5\-amzn\-6 | HDFS service for managing the Hadoop filesystem journal on HA clusters\. | 
| hadoop\-httpfs\-server | 2\.8\.5\-amzn\-6 | HTTP endpoint for HDFS operations\. | 
| hadoop\-kms\-server | 2\.8\.5\-amzn\-6 | Cryptographic key management server based on Hadoop's KeyProvider API\. | 
| hadoop\-mapred | 2\.8\.5\-amzn\-6 | MapReduce execution engine libraries for running a MapReduce application\. | 
| hadoop\-yarn\-nodemanager | 2\.8\.5\-amzn\-6 | YARN service for managing containers on an individual node\. | 
| hadoop\-yarn\-resourcemanager | 2\.8\.5\-amzn\-6 | YARN service for allocating and managing cluster resources and distributed applications\. | 
| hadoop\-yarn\-timeline\-server | 2\.8\.5\-amzn\-6 | Service for retrieving current and historical information for YARN applications\. | 
| hbase\-hmaster | 1\.4\.13 | Service for an HBase cluster responsible for coordination of Regions and execution of administrative commands\. | 
| hbase\-region\-server | 1\.4\.13 | Service for serving one or more HBase regions\. | 
| hbase\-client | 1\.4\.13 | HBase command\-line client\. | 
| hbase\-rest\-server | 1\.4\.13 | Service providing a RESTful HTTP endpoint for HBase\. | 
| hbase\-thrift\-server | 1\.4\.13 | Service providing a Thrift endpoint to HBase\. | 
| hcatalog\-client | 2\.3\.6\-amzn\-2 | The 'hcat' command line client for manipulating hcatalog\-server\. | 
| hcatalog\-server | 2\.3\.6\-amzn\-2 | Service providing HCatalog, a table and storage management layer for distributed applications\. | 
| hcatalog\-webhcat\-server | 2\.3\.6\-amzn\-2 | HTTP endpoint providing a REST interface to HCatalog\. | 
| hive\-client | 2\.3\.6\-amzn\-2 | Hive command line client\. | 
| hive\-hbase | 2\.3\.6\-amzn\-2 | Hive\-hbase client\. | 
| hive\-metastore\-server | 2\.3\.6\-amzn\-2 | Service for accessing the Hive metastore, a semantic repository storing metadata for SQL on Hadoop operations\. | 
| hive\-server2 | 2\.3\.6\-amzn\-2 | Service for accepting Hive queries as web requests\. | 
| hudi | 0\.5\.2\-incubating | Incremental processing framework to power data pipline at low latency and high efficiency\. | 
| hudi\-presto | 0\.5\.2\-incubating | Bundle library for running Presto with Hudi\. | 
| hue\-server | 4\.6\.0 | Web application for analyzing data using Hadoop ecosystem applications | 
| jupyterhub | 1\.1\.0 | Multi\-user server for Jupyter notebooks | 
| livy\-server | 0\.7\.0\-incubating | REST interface for interacting with Apache Spark | 
| nginx | 1\.12\.1 | nginx \[engine x\] is an HTTP and reverse proxy server | 
| mahout\-client | 0\.13\.0 | Library for machine learning\. | 
| mxnet | 1\.5\.1 | A flexible, scalable, and efficient library for deep learning\. | 
| mariadb\-server | 5\.5\.64 | MySQL database server\. | 
| nvidia\-cuda | 9\.2\.88 | Nvidia drivers and Cuda toolkit | 
| oozie\-client | 5\.2\.0 | Oozie command\-line client\. | 
| oozie\-server | 5\.2\.0 | Service for accepting Oozie workflow requests\. | 
| opencv | 3\.4\.0 | Open Source Computer Vision Library\. | 
| phoenix\-library | 4\.14\.3\-HBase\-1\.4 | The phoenix libraries for server and client | 
| phoenix\-query\-server | 4\.14\.3\-HBase\-1\.4 | A light weight server providing JDBC access as well as Protocol Buffers and JSON format access to the Avatica API  | 
| presto\-coordinator | 0\.232 | Service for accepting queries and managing query execution among presto\-workers\. | 
| presto\-worker | 0\.232 | Service for executing pieces of a query\. | 
| presto\-client | 0\.232 | Presto command\-line client which is installed on an HA cluster's stand\-by masters where Presto server is not started\. | 
| pig\-client | 0\.17\.0 | Pig command\-line client\. | 
| r | 3\.4\.3 | The R Project for Statistical Computing | 
| ranger\-kms\-server | 1\.2\.0 | Apache Ranger Key Management System | 
| spark\-client | 2\.4\.5\-amzn\-0 | Spark command\-line clients\. | 
| spark\-history\-server | 2\.4\.5\-amzn\-0 | Web UI for viewing logged events for the lifetime of a completed Spark application\. | 
| spark\-on\-yarn | 2\.4\.5\-amzn\-0 | In\-memory execution engine for YARN\. | 
| spark\-yarn\-slave | 2\.4\.5\-amzn\-0 | Apache Spark libraries needed by YARN slaves\. | 
| sqoop\-client | 1\.4\.7 | Apache Sqoop command\-line client\. | 
| tensorflow | 1\.14\.0 | TensorFlow open source software library for high performance numerical computation\. | 
| tez\-on\-yarn | 0\.9\.2 | The tez YARN application and libraries\. | 
| webserver | 2\.4\.25\+ | Apache HTTP server\. | 
| zeppelin\-server | 0\.8\.2 | Web\-based notebook that enables interactive data analytics\. | 
| zookeeper\-server | 3\.4\.14 | Centralized service for maintaining configuration information, naming, providing distributed synchronization, and providing group services\. | 
| zookeeper\-client | 3\.4\.14 | ZooKeeper command line client\. | 

## Configuration classifications<a name="emr-5300-class"></a>

Configuration classifications allow you to customize applications\. These often correspond to a configuration XML file for the application, such as `hive-site.xml`\. For more information, see [Configure applications](emr-configure-apps.md)\.


**emr\-5\.30\.0 classifications**  

| Classifications | Description | 
| --- | --- | 
| capacity\-scheduler | Change values in Hadoop's capacity\-scheduler\.xml file\. | 
| container\-log4j | Change values in Hadoop YARN's container\-log4j\.properties file\. | 
| core\-site | Change values in Hadoop's core\-site\.xml file\. | 
| emrfs\-site | Change EMRFS settings\. | 
| flink\-conf | Change flink\-conf\.yaml settings\. | 
| flink\-log4j | Change Flink log4j\.properties settings\. | 
| flink\-log4j\-yarn\-session | Change Flink log4j\-yarn\-session\.properties settings\. | 
| flink\-log4j\-cli | Change Flink log4j\-cli\.properties settings\. | 
| hadoop\-env | Change values in the Hadoop environment for all Hadoop components\. | 
| hadoop\-log4j | Change values in Hadoop's log4j\.properties file\. | 
| hadoop\-ssl\-server | Change hadoop ssl server configuration | 
| hadoop\-ssl\-client | Change hadoop ssl client configuration | 
| hbase | Amazon EMR\-curated settings for Apache HBase\. | 
| hbase\-env | Change values in HBase's environment\. | 
| hbase\-log4j | Change values in HBase's hbase\-log4j\.properties file\. | 
| hbase\-metrics | Change values in HBase's hadoop\-metrics2\-hbase\.properties file\. | 
| hbase\-policy | Change values in HBase's hbase\-policy\.xml file\. | 
| hbase\-site | Change values in HBase's hbase\-site\.xml file\. | 
| hdfs\-encryption\-zones | Configure HDFS encryption zones\. | 
| hdfs\-site | Change values in HDFS's hdfs\-site\.xml\. | 
| hcatalog\-env | Change values in HCatalog's environment\. | 
| hcatalog\-server\-jndi | Change values in HCatalog's jndi\.properties\. | 
| hcatalog\-server\-proto\-hive\-site | Change values in HCatalog's proto\-hive\-site\.xml\. | 
| hcatalog\-webhcat\-env | Change values in HCatalog WebHCat's environment\. | 
| hcatalog\-webhcat\-log4j2 | Change values in HCatalog WebHCat's log4j2\.properties\. | 
| hcatalog\-webhcat\-site | Change values in HCatalog WebHCat's webhcat\-site\.xml file\. | 
| hive\-beeline\-log4j2 | Change values in Hive's beeline\-log4j2\.properties file\. | 
| hive\-parquet\-logging | Change values in Hive's parquet\-logging\.properties file\. | 
| hive\-env | Change values in the Hive environment\. | 
| hive\-exec\-log4j2 | Change values in Hive's hive\-exec\-log4j2\.properties file\. | 
| hive\-llap\-daemon\-log4j2 | Change values in Hive's llap\-daemon\-log4j2\.properties file\. | 
| hive\-log4j2 | Change values in Hive's hive\-log4j2\.properties file\. | 
| hive\-site | Change values in Hive's hive\-site\.xml file | 
| hiveserver2\-site | Change values in Hive Server2's hiveserver2\-site\.xml file | 
| hue\-ini | Change values in Hue's ini file | 
| httpfs\-env | Change values in the HTTPFS environment\. | 
| httpfs\-site | Change values in Hadoop's httpfs\-site\.xml file\. | 
| hadoop\-kms\-acls | Change values in Hadoop's kms\-acls\.xml file\. | 
| hadoop\-kms\-env | Change values in the Hadoop KMS environment\. | 
| hadoop\-kms\-log4j | Change values in Hadoop's kms\-log4j\.properties file\. | 
| hadoop\-kms\-site | Change values in Hadoop's kms\-site\.xml file\. | 
| hudi\-env | Change values in the Hudi environment\. | 
| jupyter\-notebook\-conf | Change values in Jupyter Notebook's jupyter\_notebook\_config\.py file\. | 
| jupyter\-hub\-conf | Change values in JupyterHubs's jupyterhub\_config\.py file\. | 
| jupyter\-s3\-conf | Configure Jupyter Notebook S3 persistence\. | 
| jupyter\-sparkmagic\-conf | Change values in Sparkmagic's config\.json file\. | 
| livy\-conf | Change values in Livy's livy\.conf file\. | 
| livy\-env | Change values in the Livy environment\. | 
| livy\-log4j | Change Livy log4j\.properties settings\. | 
| mapred\-env | Change values in the MapReduce application's environment\. | 
| mapred\-site | Change values in the MapReduce application's mapred\-site\.xml file\. | 
| oozie\-env | Change values in Oozie's environment\. | 
| oozie\-log4j | Change values in Oozie's oozie\-log4j\.properties file\. | 
| oozie\-site | Change values in Oozie's oozie\-site\.xml file\. | 
| phoenix\-hbase\-metrics | Change values in Phoenix's hadoop\-metrics2\-hbase\.properties file\. | 
| phoenix\-hbase\-site | Change values in Phoenix's hbase\-site\.xml file\. | 
| phoenix\-log4j | Change values in Phoenix's log4j\.properties file\. | 
| phoenix\-metrics | Change values in Phoenix's hadoop\-metrics2\-phoenix\.properties file\. | 
| pig\-env | Change values in the Pig environment\. | 
| pig\-properties | Change values in Pig's pig\.properties file\. | 
| pig\-log4j | Change values in Pig's log4j\.properties file\. | 
| presto\-log | Change values in Presto's log\.properties file\. | 
| presto\-config | Change values in Presto's config\.properties file\. | 
| presto\-password\-authenticator | Change values in Presto's password\-authenticator\.properties file\. | 
| presto\-env | Change values in Presto's presto\-env\.sh file\. | 
| presto\-node | Change values in Presto's node\.properties file\. | 
| presto\-connector\-blackhole | Change values in Presto's blackhole\.properties file\. | 
| presto\-connector\-cassandra | Change values in Presto's cassandra\.properties file\. | 
| presto\-connector\-hive | Change values in Presto's hive\.properties file\. | 
| presto\-connector\-jmx | Change values in Presto's jmx\.properties file\. | 
| presto\-connector\-kafka | Change values in Presto's kafka\.properties file\. | 
| presto\-connector\-localfile | Change values in Presto's localfile\.properties file\. | 
| presto\-connector\-memory | Change values in Presto's memory\.properties file\. | 
| presto\-connector\-mongodb | Change values in Presto's mongodb\.properties file\. | 
| presto\-connector\-mysql | Change values in Presto's mysql\.properties file\. | 
| presto\-connector\-postgresql | Change values in Presto's postgresql\.properties file\. | 
| presto\-connector\-raptor | Change values in Presto's raptor\.properties file\. | 
| presto\-connector\-redis | Change values in Presto's redis\.properties file\. | 
| presto\-connector\-redshift | Change values in Presto's redshift\.properties file\. | 
| presto\-connector\-tpch | Change values in Presto's tpch\.properties file\. | 
| presto\-connector\-tpcds | Change values in Presto's tpcds\.properties file\. | 
| ranger\-kms\-dbks\-site | Change values in dbks\-site\.xml file of Ranger KMS\. | 
| ranger\-kms\-site | Change values in ranger\-kms\-site\.xml file of Ranger KMS\. | 
| ranger\-kms\-env | Change values in the Ranger KMS environment\. | 
| ranger\-kms\-log4j | Change values in kms\-log4j\.properties file of Ranger KMS\. | 
| ranger\-kms\-db\-ca | Change values for CA file on S3 for MySQL SSL connection with Ranger KMS\. | 
| recordserver\-env | Change values in the EMR RecordServer environment\. | 
| recordserver\-conf | Change values in EMR RecordServer's erver\.properties file\. | 
| recordserver\-log4j | Change values in EMR RecordServer's log4j\.properties file\. | 
| spark | Amazon EMR\-curated settings for Apache Spark\. | 
| spark\-defaults | Change values in Spark's spark\-defaults\.conf file\. | 
| spark\-env | Change values in the Spark environment\. | 
| spark\-hive\-site | Change values in Spark's hive\-site\.xml file | 
| spark\-log4j | Change values in Spark's log4j\.properties file\. | 
| spark\-metrics | Change values in Spark's metrics\.properties file\. | 
| sqoop\-env | Change values in Sqoop's environment\. | 
| sqoop\-oraoop\-site | Change values in Sqoop OraOop's oraoop\-site\.xml file\. | 
| sqoop\-site | Change values in Sqoop's sqoop\-site\.xml file\. | 
| tez\-site | Change values in Tez's tez\-site\.xml file\. | 
| yarn\-env | Change values in the YARN environment\. | 
| yarn\-site | Change values in YARN's yarn\-site\.xml file\. | 
| zeppelin\-env | Change values in the Zeppelin environment\. | 
| zookeeper\-config | Change values in ZooKeeper's zoo\.cfg file\. | 
| zookeeper\-log4j | Change values in ZooKeeper's log4j\.properties file\. | 