# Big Data Technology Index(大数据技术索引)


1. 大数据生态
    1. bigdata-ecosystem
        1. https://github.com/zenkay/bigdata-ecosystem
        2. http://bigdata.andreamostosi.name/
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
3. 数据可视化
    1. superset：
        1. https://superset.incubator.apache.org/
    2. 报表工具  https://git.oschina.net/max256/morpho
    3. 关联技术
        1. 前端技术
            1. echarts
                1. http://echarts.baidu.com/
            2. antv
                1.  https://antv.alipay.com/zh-cn/index.html
    4. cboard 开源BI仪表板平台，支持交互式多维报表设计和数据分析
        1. https://github.com/yzhang921/CBoard
    5. datav  阿里云的数据可视化产品
4. 数据同步
    1. 数据传输
        1. kafka: a distibuted streaming platform
            1. http://kafka.apache.org/
            2. 关联生态
                1. https://www.confluent.io/
                    1. KSQL - the Streaming SQL Engine for Apache Kafka  https://github.com/confluentinc/ksql
                        1. KSQL is an open source streaming SQL engine for Apache Kafka. It provides a simple and completely interactive SQL interface for stream processing on Kafka; no need to write code in a programming language such as Java or Python. KSQL is open-source (Apache 2.0 licensed), distributed, scalable, reliable, and real-time. It supports a wide range of powerful stream processing operations including aggregations, joins, windowing, sessionization, and much more.
        2. ActiveMQ
        3. RabbitMQ
    2. 日志收集
        1. flume
            1. Flume is a distributed, reliable, and available service for efficiently collecting, aggregating, and moving large amounts of log data. It has a simple and flexible architecture based on streaming data flows. It is robust and fault tolerant with tunable reliability mechanisms and many failover and recovery mechanisms. It uses a simple extensible data model that allows for online analytic application.
            2. http://flume.apache.org/
        2. logstash
            1. https://www.ibm.com/developerworks/cn/opensource/os-cn-elk-filebeat/index.html?ca=drs-&utm_source=tuicool&utm_medium=referral
    3. 分布式数据库同步
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

    4. 自动化数据同步流
        1. http://nifi.apache.org/
    5. 数据同步工具
        1. mysql replication protocal go 实现： https://github.com/siddontang/go-mysql
        2. mysql replication protocal python 实现 https://github.com/noplay/python-mysql-replication
5. ETL
    1. KETTLE
        1. https://community.hds.com/docs/DOC-1009855
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
7. 计算引擎&框架
    1. spark
        1. http://spark.apache.org/
    2. taz
    3. hadoop-mapreduce
        1. http://hadoop.apache.org/
    4. bigflow
        1. https://github.com/baidu/bigflow
    5. storm
    7. flink
        1. Apache Flink® is an open-source stream processing framework for distributed, high-performing, always-available, and accurate data streaming applications.
        2. http://flink.apache.org/
    8. hive
        1. The Apache Hive ™ data warehouse software facilitates reading, writing, and managing large datasets residing in distributed storage using SQL. Structure can be projected onto data already in storage. A command line tool and JDBC driver are provided to connect users to Hive.
        2. http://hive.apache.org/
    9. impala
8. 流式计算的一些解决方案
    1. 宜信技术研发中心Wormhole
        1. Wormhole 是一个一站式流式处理云平台解决方案（SPaaS - Stream Processing as a Service）。 面向大数据流式处理项目的开发管理运维人员，致力于提供统一抽象的概念体系，直观可视化的操作界面，简单流畅的配置管理流程，基于 SQL 即可完成的业务逻辑开发方式，并且屏蔽了流式处理的底层技术细节，极大的降低了数据项目管理运维门槛，使得大数据流式处理项目的开发管理运维变得更加轻量敏捷可控可靠。
            1. https://github.com/edp963/wormhole
        2. Moonbox是一个DCaaS（Data Computation as a Service）平台解决方案。Moonbox面向数据仓库工程师/数据分析师/数据科学家等，致力于提供数据虚拟化解决方案。既可作为数据应用底层数据查询计算统一入口，也可作为逻辑数据仓库与现有数据仓库互补。用户只需通过统一SQL服务调用和Moonbox交互，即可透明屏蔽异构数据系统异构交互方式，轻松实现跨异构数据系统Adhoc混算。
            1. https://github.com/edp963/moonbox
    2. https://www.confluent.io/
        1. KSQL
9. 大数据存储
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
    5. prestodb 开源的分布式SQL交互式解析查询引擎
        1. Distributed SQL Query Engine for Big Data
        2. https://prestodb.io/
        3. http://prestodb-china.com/
        4. https://github.com/CHINA-JD/presto/
    7. 分布式文件存储
        1. https://github.com/chrislusf/seaweedfs


