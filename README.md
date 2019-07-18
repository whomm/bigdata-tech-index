# Big Data Technology Index/大数据技术索引

1. Bigdata-ecosystem(大数据生态)
    1. bigdata-ecosystem
        1. https://github.com/zenkay/bigdata-ecosystem
        2. http://bigdata.andreamostosi.name/
    2. Great Power, Great Responsibility: The 2018 Big Data & AI Landscape
        1. http://mattturck.com/bigdata2018/
        2. http://mattturck.com/wp-content/uploads/2018/07/Matt_Turck_FirstMark_Big_Data_Landscape_2018_Final.png
        3. http://mattturck.com/bigdata2017/
    3. A curated list of amazingly awesome Hadoop and Hadoop ecosystem resources https://github.com/youngwookim/awesome-hadoop
2. 国内外相关
    1. 国内数据分析计算平台产品
        1. 神策
            1. https://www.sensorsdata.cn
                1. https://www.sensorsdata.cn/blog/technical_implementation_of_sensors_analytics/
                2. https://www.sensorsdata.cn/manual/
        2. growingio
            1. https://www.growingio.com/
        3. 海致：
            1. https://www.bdp.cn/home.html
        4. 阿里云 quick bi
            1. https://data.aliyun.com/product/bi
        5. finebi
            1. http://www.finebi.com/
                1. finereport
                2. http://www.finereport.com/
    2. 国外数据分析平台
        1. tableau 数据分析：
            1. https://www.tableau.com/
        2. http://www.pentaho.com/
            1. ETL
                1. KETTLE
                    1. Pentaho Data Integration ( ETL ) 1.k.a Kettle
                    2. https://github.com/pentaho/pentaho-kettle
                    3. https://wiki.pentaho.com/display/COM/Community+Wiki+Home
        3. http://www.spagobi.org/
        4. https://www.bmc.com/
            1. CONTROL-M
                1. Control-M 是一套 数字业务自动化解决方案，能够简化并自动化各种批处理应用工作负载。在基础架构、数据和应用程序中优化 SLA 并加速应用程序部署。
                2. http://www.bmcsoftware.cn/it-solutions/control-m.html
                3. http://www.doc88.com/p-1863463402569.html
        5. https://www.teradata.com.cn
            1.
3. Data visualization(数据可视化)
    1. superset：
        1. https://superset.incubator.apache.org/
    2. Metabase:
        1. https://www.metabase.com/
        2. Metabase is the easy, open source way for everyone in your company to ask questions and learn from data.
        3. https://github.com/metabase/metabase
    3. redash:
        1. https://redash.io/
        2. Connect and query your data sources, build dashboards to visualize data and share them with your company
    4. cboard
        1. 开源BI仪表板平台，支持交互式多维报表设计和数据分析
        2. https://github.com/yzhang921/CBoard
    5. datav  阿里云的数据可视化产品
    6. morpho
        1. 支持完善报表系统
        2. https://git.oschina.net/max256/morpho
    7. 关联技术
        1. 前端技术
            1. echarts
                1. http://echarts.baidu.com/
            2. antv
                1.  https://antv.alipay.com/zh-cn/index.html

4. Data synchronization(数据同步)
    1. 数据传输
        1. kafka: a distibuted streaming platform
            1. http://kafka.apache.org/
            2. 相关文章
                1. Uber如何搭建一个基于Kafka的跨数据中心复制平台 https://mp.weixin.qq.com/s/tZmrF2EXU-zv4XTx-3frMA
            3. 关联生态
                1. https://www.confluent.io/
                    1. KSQL - the Streaming SQL Engine for Apache Kafka  https://github.com/confluentinc/ksql
                        1. KSQL is an open source streaming SQL engine for Apache Kafka. It provides a simple and completely interactive SQL interface for stream processing on Kafka; no need to write code in a programming language such as Java or Python. KSQL is open-source (Apache 2.0 licensed), distributed, scalable, reliable, and real-time. It supports a wide range of powerful stream processing operations including aggregations, joins, windowing, sessionization, and much more.
        2. ActiveMQ
        3. RabbitMQ
        4. beanstalkd
            1. 官方：https://beanstalkd.github.io/
            2. github: https://github.com/beanstalkd/beanstalkd
            3. beanstalkd简介 https://www.jianshu.com/p/391d847dc872
        5. LogDevice (facebook)
            1. https://github.com/facebookincubator/LogDevice
        6. Confluo
            1. https://ucbrise.github.io/confluo/
            2. 伯克利开源 Confluo：吞吐量比 Kafka 高 4 到 10 倍！ https://mp.weixin.qq.com/s/DfDVwxEGXLpyhdXHHCSGTg
        7. Pulsar
            1. Apache Pulsar is an open-source distributed pub-sub messaging system originally created at Yahoo and now part of the Apache Software Foundation
            2. http://pulsar.apache.org/
            3. 被视为代替Kafka的消息队列：Apache Pulsar设计简介 https://zhuanlan.zhihu.com/p/64901908
            4. Apache Pulsar — Gentle Introduction https://medium.com/@pckeyan/apache-pulsar-gentle-introduction-465ca6da0e18
            5. 如何基于Apache Pulsar和Spark进行批流一体的弹性数据处理？ https://mp.weixin.qq.com/s?__biz=MzU1NDA4NjU2MA==&mid=2247496990&idx=2&sn=1b230ead0d3387ddb92a36f3e9d6ea59&chksm=fbea4cd1cc9dc5c79b43212396cbb09ed1cecf6c5806d5dbb593429ddf5f25a63746ab25c7ee&mpshare=1&scene=1&srcid=#rd
        8. 相关文章
            1. 独家解读！京东高可用分布式流数据存储的架构设计 http://www.raincent.com/content-85-13490-1.html
    2. 日志收集
        1. flume
            1. Flume is a distributed, reliable, and available service for efficiently collecting, aggregating, and moving large amounts of log data. It has a simple and flexible architecture based on streaming data flows. It is robust and fault tolerant with tunable reliability mechanisms and many failover and recovery mechanisms. It uses a simple extensible data model that allows for online analytic application.
            2. http://flume.apache.org/
        2. logstash
            1. https://www.ibm.com/developerworks/cn/opensource/os-cn-elk-filebeat/index.html?ca=drs-&utm_source=tuicool&utm_medium=referral
        3. logkit（qiniu云）
            https://github.com/qiniu/logkit
    3. 分布式数据库同步/streaming
        1. https://github.com/alibaba/otter
            1. canal mysql数据同步 https://github.com/alibaba/canal
        2. DataX
            1. DataX 是阿里巴巴集团内被广泛使用的离线数据同步工具/平台，实现包括 MySQL、Oracle、SqlServer、Postgre、HDFS、Hive、ADS、HBase、TableStore(OTS)、MaxCompute(ODPS)、DRDS 等各种异构数据源之间高效的数据同步功能。
            2. https://github.com/alibaba/DataX
        3. dbus   https://github.com/BriData/DBus
            1. 专注于数据的收集及实时数据流计算，通过简单灵活的配置，以无侵入的方式对源端数据进行采集，采用高可用的流式计算框架，对公司各个IT系统在业务流程中产生的数据进行汇聚，经过转换处理后成为统一JSON的数据格式（UMS），提供给不同数据使用方订阅和消费，充当数仓平台、大数据分析平台、实时报表和实时营销等业务的数据源。
            2. https://bridata.github.io/DBus/
            3. http://dbaplus.cn/news-21-872-1.html
            4. http://dbaplus.cn/news-134-1860-1.html
        4. mypip
            1. https://github.com/mardambey/mypipe/
        5. sqoop
            1. Apache Sqoop(TM) is a tool designed for efficiently transferring bulk data between Apache Hadoop and structured datastores such as relational databases.
            2. http://sqoop.apache.org/
        6. kafka-connect-jdbc is a Kafka Connector for loading data to and from any JDBC-compatible database.
            1. https://github.com/confluentinc/kafka-connect-jdbc
        7. Debezium（Stream changes from your databases） http://debezium.io/
            1. Debezium is an open source distributed platform for change data capture. Start it up, point it at your databases, and your apps can start responding to all of the inserts, updates, and deletes that other apps commit to your databases. Debezium is durable and fast, so your apps can respond quickly and never miss an event, even when things go wrong.
        8. cannel
            1. 阿里巴巴mysql数据库binlog的增量订阅&消费组件 。阿里云DRDS( https://www.aliyun.com/product/drds )、阿里巴巴TDDL 二级索引、小表复制powerd by canal. Aliyun Data Lake Analytics https://www.aliyun.com/product/datalakeanalytics powered by canal
        9. otter 阿里巴巴分布式数据库同步系统(解决中美异地机房)
            1. https://github.com/alibaba/otter
        10. 阿里云dts
            1. https://help.aliyun.com/document_detail/26592.html?spm=a2c4g.11174283.6.542.7df07b02aXfWXN
        11. 阿里愚公： 阿里巴巴去Oracle数据迁移同步工具(全量+增量,目标支持MySQL/DRDS)
            1. http://github.com/alibaba/yugong
        12. databus
            1. Source-agnostic distributed change data capture system
            2. https://github.com/linkedin/databus
        13 dbevents
            1. Uber 推出数据湖集成神器 DBEvents，支持 MySQL、Cassandra 等 https://www.infoq.cn/article/7iYW0ZepClsMW-TDTakc

    4. 自动化数据同步流
        1. http://nifi.apache.org/
    5. 数据同步工具
        1. mysql replication protocal go 实现： https://github.com/siddontang/go-mysql
        2. mysql replication protocal python 实现 https://github.com/noplay/python-mysql-replication
    6. DBEvents
        1. https://www.infoq.cn/article/7iYW0ZepClsMW-TDTakc
5. ETL

    1. KETTLE
        1. https://community.hds.com/docs/DOC-1009855
    2. Talend
        1. https://www.talend.com/
        2. 开源产品国内也提供技术支持
    3. informatica
        1. 商业产品+技术服务收费
    4. 相关文档
        1. informatica  Talend 有竞争关系
        2. 几种 ETL 工具的比较(Kettle,Talend,Informatica 等) https://www.cnblogs.com/journeyIT/p/8267223.html

6. 离线任务调度
    1. hadoop任务调度
        1. http://oozie.apache.org/
        2. https://azkaban.github.io/
    2. Quartz
        1. http://www.quartz-scheduler.org/
    3. 原阿里宙斯 zeue
        1. https://github.com/ctripcorp/dataworks-zeus
    4. 个人开源任务调度
        1.  https://github.com/xuxueli/xxl-job
    5. control-m
        1. https://baike.baidu.com/item/control-m/176677?fr=aladdin
    7. 数据平台作业调度和实践
        1. https://www.jianshu.com/p/bddffdfea00b
        2. https://www.jianshu.com/p/428ae367a38b
    8. autosys
    9. etl-automation
    10. tws (ibm)
    11. TASKCTL
        1. http://www.taskctl.com/Service/Document
    12. JobCtrl
        1. 海量任务作业调度监控平台 - Primeton JobCtrl
        2. http://www.primeton.com/
    13. airflow
        1. Airflow is a platform to programmatically author, schedule and monitor workflows.(airbnb家的基于DAG(有向无环图)的任务管理系统)
        2. http://airflow.incubator.apache.org/
        3. [译] 解密 Airbnb 的数据流编程神器：Airflow 中的技巧和陷阱 https://segmentfault.com/a/1190000005078547
    14. azkaban
        1. Azkaban was designed primarily with usability in mind. It has been running at LinkedIn for several years, and drives many of their Hadoop and data warehouse processes.
        2. https://azkaban.github.io/
    15. luigi
        1. helps you build complex pipelines of batch jobs. It handles dependency resolution, workflow management, visualization, handling failures, command line integration, and much more.
        2. http://luigi.readthedocs.io/en/stable/
    16. Oozie
        1. Apache Oozie Workflow Scheduler for Hadoop
        2. http://oozie.apache.org/
    17. TBSchedule
        1. https://www.jianshu.com/p/d7b55b7ee75f
    18. Elastic-Job
        1. Elastic-Job is a distributed scheduling solution consisting of two separate projects, Lite and Cloud.
        2. https://github.com/elasticjob
7. 计算引擎&框架
    1. spark
        1. http://spark.apache.org/
        2. 相关资料
            1. spark at Adobe: https://pan.baidu.com/s/1BGH4G4XxYVlXEsYWsK2t6Q
            2. Uber Hudi Spark: https://pan.baidu.com/s/1ykYbIoVm4HMkS32t6pxkPg
            3. uber/hudi https://github.com/uber/hudi/wiki/ASF-Proposal
            4. 如何使用redis和apache spark 处理实时数据？ http://www.360doc.com/content/19/0615/15/7669533_842608030.shtml
    2. tez
    3. hadoop-mapreduce
        1. http://hadoop.apache.org/
    4. bigflow
        1. https://github.com/baidu/bigflow
    5. storm
    7. flink
        1. Apache Flink® is an open-source stream processing framework for distributed, high-performing, always-available, and accurate data streaming applications.
        2. http://flink.apache.org/
        3. 360 深度实践：Flink 与 Storm 协议级对比 https://www.chainnews.com/articles/034685815019.htm
    8. blink
        1. Blink 有何特别之处？菜鸟供应链场景最佳实践 https://segmentfault.com/a/1190000019282277
    9. sql计算引擎
        1. hive
            1. The Apache Hive ™ data warehouse software facilitates reading, writing, and managing large datasets residing in distributed storage using SQL. Structure can be projected onto data already in storage. A command line tool and JDBC driver are provided to connect users to Hive.
            2. http://hive.apache.org/
        2. impala
            1. Impala 在 Hulu 中的优化和改进 http://itindex.net/detail/59411-impala-hulu-%E4%BC%98%E5%8C%96
        3. Apache Drill
            1. Schema-free SQL Query Engine for Hadoop, NoSQL and Cloud Storage
            2. http://drill.apache.org/
        4. prestodb 开源的分布式SQL交互式解析查询引擎
            1. Distributed SQL Query Engine for Big Data
            2. https://prestodb.io/
            3. http://prestodb-china.com/
            4. https://github.com/CHINA-JD/presto/
        5. verdictdb
            1. 200x Fewer Resources No Changes to the Application Compatible with All SQL Engines
            2. http://verdictdb.org/
        6. Phoenix
            1. HBase进化之从NoSQL到NewSQL，凤凰涅槃成就Phoenix https://yq.aliyun.com/articles/680772
            2. 阿里云HBase SQL（Phoenix）服务深度解读 https://yq.aliyun.com/articles/703234

8. 流式计算的一些解决方案
    1. 宜信技术研发中心Wormhole
        1. Wormhole 是一个一站式流式处理云平台解决方案（SPaaS - Stream Processing as a Service）。 面向大数据流式处理项目的开发管理运维人员，致力于提供统一抽象的概念体系，直观可视化的操作界面，简单流畅的配置管理流程，基于 SQL 即可完成的业务逻辑开发方式，并且屏蔽了流式处理的底层技术细节，极大的降低了数据项目管理运维门槛，使得大数据流式处理项目的开发管理运维变得更加轻量敏捷可控可靠。
            1. https://github.com/edp963/wormhole
        2. Moonbox是一个DCaaS（Data Computation as a Service）平台解决方案。Moonbox面向数据仓库工程师/数据分析师/数据科学家等，致力于提供数据虚拟化解决方案。既可作为数据应用底层数据查询计算统一入口，也可作为逻辑数据仓库与现有数据仓库互补。用户只需通过统一SQL服务调用和Moonbox交互，即可透明屏蔽异构数据系统异构交互方式，轻松实现跨异构数据系统Adhoc混算。
            1. https://github.com/edp963/moonbox
    2. https://www.confluent.io/
        1. KSQL
            1. quickstart：
                1. download & start:
                    1. https://www.confluent.io/download/
                    2. https://docs.confluent.io/current/quickstart/cos-quickstart.html
                2. other: https://github.com/confluentinc/ksql/tree/0.1.x/docs/quickstart#setup
            2. https://www.confluent.io/blog/ksql-open-source-streaming-sql-for-apache-kafka/
            3. https://www.confluent.io/blog/exactly-once-semantics-are-possible-heres-how-apache-kafka-does-it/
            4. KSQL in Action: Enriching CSV Events with Data from RDBMS into AWS https://www.confluent.io/blog/ksql-in-action-enriching-csv-events-with-data-from-rdbms-into-AWS/
    3. Stream computing engine(流计算引擎)：
        1. Flink
        2. Spark
        3. Kafka
        4. Pulsar
        5. Storm
        6. JStorm
        7. nifi
        8. samza
    4. 相关文档：
        1. 解读2018：13家开源框架谁能统一流计算？ https://mp.weixin.qq.com/s/DKGEiW-WozhKXr7b3zz4Ow
9. Large Data Storage(大数据存储)
    1. OLAP（On-Line Analytical Processing）
        1. PALO
            1. 百度数据仓库Palo是百度云上提供的PB级别的MPP数据仓库服务，以较低的成本提供在大数据集上的高性能分析和报表查询功能。
            2. 百度数据仓库Palo不是面向OLTP的数据库产品，而是一款面向OLAP的数据库产品，和百度数据仓库Palo功能定位比较相似的产品包括Greenplum、Vertica、Exadata等商业数据仓库系统和Amazon RedShift、Google BigQuery等云服务，大家可以参考以上产品来理解百度数据仓库Palo。
        2. https://cloud.baidu.com/doc/PALO/System.html#.E7.B3.BB.E7.BB.9F.E6.9E.B6.E6.9E.84
        3. tidb 国产开源分布式newsql关系型数据库 （完美兼容mysql）
            1. https://pingcap.com/index.html
        4. QingCloud RadonDB 是基于 MySQL 研发的新一代分布式关系型数据库，可无限水平扩展，支持分布式事务，具备金融级数据强一致性，满足企业级核心数据库对大容量、高并发、高可靠及高可用的极致要求。
            1. https://github.com/radondb/radon
        5. kudu   开源分布式 nosql olap数据库
            1.  a new addition to the open source Apache Hadoop ecosystem, Apache Kudu completes Hadoop's storage layer to enable fast analytics on fast data.
            2. http://kudu.apache.org/
            3. 产考文档：
                1. 小米kudu实时分析系统&kudu、hbase、parquet对比  https://baijia.baidu.com/s?old_id=581124
        6. kylin
            1. Apache Kylin™是一个开源的分布式分析引擎，提供Hadoop/Spark之上的SQL查询接口及多维分析（OLAP）能力以支持超大规模数据，最初由eBay Inc. 开发并贡献至开源社区。它能在亚秒内查询巨大的Hive表。
            2. http://kylin.apache.org/
        7. greenplum
            1. Greenplum DB 号称是世界上第一个开源的大规模并行数据仓库，最初是基于 PostgreSQL，现在已经添加了大量数据库方面的创新。Greenplum 提供 PD 级别数据量的强大和快速分析能力，特别是面向大数据方面的分析能力，支持大数据的超高性能分析查询。
            2. https://greenplum.org/
            3. http://www.greenplum.net.cn/
            4. 产考资料
                1. 《Greenplum资源隔离指南》 https://yq.aliyun.com/articles/57763
                2. 《三张图读懂Greenplum在企业的正确使用姿势》 https://yq.aliyun.com/articles/57736
        8. Vertica
            1. https://www.vertica.com/
        9. Exadata
        10. Amazon RedShift
        11. Google BigQuery
        12. druid: Apache Druid (incubating) is a high performance analytics data store for event-driven data.
            1. http://druid.io/
            2. eBay如何打造基于Apache Druid的大数据实时监控系统？ http://mp.weixin.qq.com/s?__biz=MjM5MDE0Mjc4MA==&mid=2651016867&idx=3&sn=8d6d32107f6aa384fbeff2bd65fd27e4&chksm=bdbeb6f08ac93fe6cda0792aeb82f2df78465dd0c00bc7195e6eeadcf3e3a862dcae5d0dc836&mpshare=1&scene=1&srcid=#rd
        13. pinot(A realtime distributed OLAP datastore https://github.com/linkedin/pinot/wiki)
            1. Pinot is a realtime distributed OLAP datastore, which is used at LinkedIn to deliver scalable real time analytics with low latency. It can ingest data from offline data sources (such as Hadoop and flat files) as well as online sources (such as Kafka). Pinot is designed to scale horizontally.
        14. OceanBase
            1. 金融级分布式关系数据库 https://oceanbase.alipay.com/
        15. cassandra
            1. The Apache Cassandra database is the right choice when you need scalability and high availability without compromising performance. Linear scalability and proven fault-tolerance on commodity hardware or cloud infrastructure make it the perfect platform for mission-critical data. Cassandra's support for replicating across multiple datacenters is best-in-class, providing lower latency for your users and the peace of mind of knowing that you can survive regional outages.
            2. http://cassandra.apache.org/
        16. ClickHouse
            1. https://clickhouse.yandex/
            2. ClickHouse is an open source column-oriented database management system capable of real time generation of analytical data reports using SQL queries.
            3. 最快开源 OLAP 引擎！ClickHouse 在头条的技术演进 https://www.infoq.cn/article/NTwo*yR2ujwLMP8WCXOE
        17. YugaByte DB
            1. YugaByte DB is a high-performance, cloud-native distributed SQL database. 
            2. YugaByte DB：高性能的分布式ACID事务的开源数据库 https://www.jdon.com/49487
            3. https://github.com/YugaByte/yugabyte-db
    2. parquet  hadoop生态下的列式存储、数据处理框架
        1. https://parquet.apache.org/
        2. 适用场景：
        3. 适用案例：
    3. Elasticsearch  是一个分布式的 RESTful 风格的搜索和数据分析引擎，能够解决不断涌现出的各种用例
        1. https://www.elastic.co/
            1. 生态关联
                1. logstash
                2. beats
                3. kibana
    4. hbase 分布式列式存储
        1. Apache HBase™ is the Hadoop database, a distributed, scalable, big data store.
        2. https://hbase.apache.org/
        3. 中文产考资料： http://abloz.com/hbase/book.html
        4. 技术延伸
            1. openTSDB 基于hbase的时间序列数据库
                1. The Scalable Time Series Database. Store and serve massive amounts of time series data without losing granularity.
                2. http://opentsdb.net/
            2. kylin
    5. 分布式文件存储
        1. https://github.com/chrislusf/seaweedfs
    6. alluxio
        1. http://www.alluxio.org/
        2. Alluxio（之前名为Tachyon）是世界上第一个以内存为中心的虚拟的分布式存储系统。它统一了数据访问的方式，为上层计算框架和底层存储系统构建了桥梁。 应用只需要连接Alluxio即可访问存储在底层任意存储系统中的数据。此外，Alluxio的以内存为中心的架构使得数据的访问速度能比现有方案快几个数量级。
        3. https://www.alluxio.org/docs/1.6/cn/
    7. OpenStack Swift
        1. Swift is a highly available, distributed, eventually consistent object/blob store. Organizations can use Swift to store lots of data efficiently, safely, and cheaply.
        2. https://docs.openstack.org/swift/latest/
    8. GlusterFS
        1. Gluster is a scalable, distributed file system that aggregates disk storage resources from multiple servers into a single global namespace.
        2. https://docs.gluster.org/en/latest/
    9. HDFS
        1. https://hadoop.apache.org/docs/r1.2.1/hdfs_design.html
    10. MaprFS
        1. MapR-FS provides high performance enterprise-grade storage for big data
        2. https://mapr.com/products/mapr-fs/
    11. Ceph  独一无二地在一个统一的系统中同时提供了对象、块、和文件存储功能。
        1. http://docs.ceph.org.cn/
    12. OSS
        1. https://cn.aliyun.com/product/oss
    13. Amazon S3
    14. CarbonData
        1. Apache CarbonData is an indexed columnar data format for fast analytics on big data platform, e.g. Apache Hadoop, Apache Spark, etc.
        2. 特点：
            1. 一种Hadoop Native的列存文件格式 索引的文件格式
            2. 一种带索引的文件格式+ Spark/Presto 计算引擎深度集成和优化的解决方案
            3. 拓展了Spark SQL 的语法，提供了数据管理的功能，拥有丰富的索引，及针对计算引擎对查询和计算进行了深度优化什么是CarbonData
        3. 相关资料：
            1. CarbonData的实践与调优Action & Tuning in CarbonData: https://pan.baidu.com/s/1MibdwHK16Usk0FXsgBx7iQ
            2. 基于CarbonData构建万亿级数据仓库 https://pan.baidu.com/s/1mTkuM_tJC-kO8hwJLjVKog
10. 干货文章
    1. 敏捷大数据（公众号：敏捷大数据）
        1. 敏捷大数据，了解一下？ https://mp.weixin.qq.com/s/N7B1P5pWxTte9Y_HjV8ksw
        2. 实时数据平台
            1. 如何设计实时数据平台（上篇） https://mp.weixin.qq.com/s/m8kqanZ6fUUcg0U94E5ptQ
            2. 如何设计实时数据平台（下篇） https://mp.weixin.qq.com/s/0zm_eVlTDmuReTJ1UTk0zg
        3. 逻辑数据仓库
            1. 如何设计逻辑数据仓库（上篇） https://mp.weixin.qq.com/s/a9sAl6PiZpOEO-u1AMkDEQ
            2. 如何设计逻辑数据仓库（中篇） https://mp.weixin.qq.com/s/4iuxTW8E8Iw-7b3yfgC88w
            3. 如何设计逻辑数据仓库（下篇） https://mp.weixin.qq.com/s/Xd6xgTqzsDtP-LFA5XtUNg
        4. 数据虚拟化
            1. 数据虚拟化环境设计步骤分解（上篇） https://mp.weixin.qq.com/s/HzuWmV1wH3uFHA3V--S-Ug
            2. 数据虚拟化环境设计步骤分解（中篇） https://mp.weixin.qq.com/s/GJFLL9VU2NoqLPdnVVETWw
            3. 数据虚拟化环境设计步骤分解（下篇） https://mp.weixin.qq.com/s/PDjV8P-YzNZYFOjnXplvEw
    2. 大数据务虚杂谈(公众号：大数据务虚杂谈) https://www.jianshu.com/nb/13273839
        1. 数据平台作业调度系统详解－理论篇 https://www.jianshu.com/p/bddffdfea00b
        2. 数据平台作业调度系统详解－实践篇 https://www.jianshu.com/p/428ae367a38b
        3. 大数据平台-元数据管理系统解析 https://www.jianshu.com/p/9fe3ff2bbe99
    3. FinanceR https://segmentfault.com/blog/harryprince
        1. 深入对比数据仓库模式：Kimball vs Inmon https://segmentfault.com/a/1190000006255954
    4. Matt Turck《Great Power, Great Responsibility: The 2018 Big Data & AI Landscape》: http://mattturck.com/bigdata2018/
    5. 2018京东大数据白皮书 https://pan.baidu.com/s/17V1wGTpfj7vsnoThlkw5Mw
    6. 大数据之路：阿里巴巴大数据实践 https://pan.baidu.com/s/1cDtSLzYb5ddzf0gDIGImqA
    7. BI和数据仓库：企业分析决策真的离不开数据仓库吗？ https://segmentfault.com/a/1190000019236409?utm_source=tag-newest
    8. SQL on Hadoop 在快手大数据平台的实践与优化 https://www.infoq.cn/article/BN9cJjg1t-QSWE6fqkoR
    9. 数据中台：宜信敏捷数据中台建设实践|分享实录 https://juejin.im/post/5cecab63f265da1bcb4f0c0d
    10. 达达-京东到家大数据平台演进实战 http://www.sohu.com/a/319825103_659464
11. Graph Platform
    1. https://www.tigergraph.com/
        1. The World’s Fastest and Most Scalable Graph Platform
        2. Through its Native Parallel Graph™ technology, TigerGraph represents what’s next in the graph database evolution: a complete, distributed, parallel graph computing platform supporting web-scale data analytics in real-time. Combining the best ideas (MapReduce, Massively Parallel Processing, and fast data compression/decompression) with fresh development, TigerGraph delivers what you’ve been waiting for: the speed, scalability, and deep exploration/querying capability to extract more business value from your data.
        3. 相关资料
            1. 图数据库 南慕伦・知乎专栏 https://zhuanlan.zhihu.com/graphdb
            2. 图数据库实战入门 —— 一个简单的电影推荐系统实现 https://zhuanlan.zhihu.com/p/38195608
    2. https://neo4j.com/
        1. 相关资料
            1. 一文揭秘！自底向上构建知识图谱全过程 https://zhuanlan.zhihu.com/p/38891715
12. Time Series Database
    1. openTSDB 基于hbase的时间序列数据库
        1. The Scalable Time Series Database. Store and serve massive amounts of time series data without losing granularity.
        2. http://opentsdb.net/
        3. 相关文章：
            1. OpenTSDB 底层 HBase 的 Rowkey 是如何设计的 https://www.iteblog.com/archives/2450.html
    2. druid: Apache Druid (incubating) is a high performance analytics data store for event-driven data.
        1. http://druid.io/
    3. InfluxDB
        1. InfluxDB是一个由InfluxData开发的开源时序型数据库。它由Go写成，着力于高性能地查询与存储时序型数据。InfluxDB被广泛应用于存储系统的监控数据，IoT行业的实时数据等场景(维基百科)。
        2. https://www.influxdata.com/
    4. TDengine
        1. TDengine is an open-sourced big data platform under GNU AGPL v3.0, designed and optimized for the Internet of Things (IoT), Connected Cars, Industrial IoT, and IT Infrastructure and Application Monitoring. Besides the 10x faster time-series database, it provides caching, stream computing, message queuing and other functionalities to reduce the complexity and cost of development and operation. TDengine是一个开源的专为物联网、车联网、工业互联网、IT运维等设计和优化的大数据平台。除核心的快10倍以上的时序数据库功能外，还提供缓存、数据订阅、流式计算等功能，最大程度减少研发和运维的工作量。
        2. https://www.taosdata.com/
        3. https://github.com/taosdata/TDengine

13. mysql to kafka
    1. 技术框架
        1. dbus
        2. Debezium
    2. 技术文档
        1. Streaming MySQL tables in real-time to Kafka https://engineeringblog.yelp.com/2016/08/streaming-mysql-tables-in-real-time-to-kafka.html
14. Data Modeling Tool(数据建模工具)
    1. https://erwin.com/
15. Cluster Management Solution(集群管理解决方案)
    1. Cloudera & Hortonworks
        1. 两家公司已经合并
    2. ambari
        1. The Apache Ambari project is aimed at making Hadoop management simpler by developing software for provisioning, managing, and monitoring Apache Hadoop clusters. Ambari provides an intuitive, easy-to-use Hadoop management web UI backed by its RESTful APIs.
        2. https://ambari.apache.org/
        3. Ambari——大数据平台的搭建利器 https://www.ibm.com/developerworks/cn/opensource/os-cn-bigdata-ambari/index.html
        4. Ambari及其HDP集群安装及其配置教程 https://zhuanlan.zhihu.com/p/37322462
16. Machine learning(机器学习)
    1. TensorFlow
    2. Horovod
        1. 是时候放弃tensorflow集群投入horovod的怀抱 https://juejin.im/post/5cbc6dbd5188253236619ccb
    3. sqlflow
        1. Brings SQL and AI together. https://sqlflow.org
    4. mlsql
        1. Unify Big Data and Machine Learning
        2. https://www.jianshu.com/p/c90acfbd4638?utm_campaign=hugo&utm_medium=reader_share&utm_content=note&utm_source=weixin-friends&from=groupmessage&isappinstalled=0
        3. MLSQL 内置Delta数据湖以及Compaction功能介绍 https://www.jianshu.com/p/239361b8bcde?utm_campaign=hugo&utm_medium=reader_share&utm_content=note&utm_source=weixin-friends&from=groupmessage&isappinstalled=0



