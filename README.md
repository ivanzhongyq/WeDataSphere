[English](README.md) | [中文](README_zh_CN.md)

## WeDataSphere Open Source Components
[DataSphere Studio](https://github.com/WeBankFinTech/DataSphereStudio), [Linkis](https://github.com/WeBankFinTech/Linkis), [Scriptis](https://github.com/WeBankFinTech/Scriptis), [Qualitis](https://github.com/WeBankFinTech/Qualitis), [Schedulis](https://github.com/WeBankFinTech/Schedulis), [Exchangis](https://github.com/WeBankFinTech/Exchangis).
<br>
![OSProjects](images/introduction/OSPprojects.png)

# *[Apache Linkis(Incubating)](https://github.com/apache/incubator-linkis)* 

**[Click me](https://github.com/apache/incubator-linkis) to Github repo**

[Linkis](https://github.com/apache/incubator-linkis) builds a computation middleware layer to decouple the upper applications and the underlying data engines, provides standardized interfaces (REST, JDBC, WebSocket etc.) to easily connect to various underlying engines (Spark, Presto, Flink, etc.), while enables cross engine context sharing, unified job& engine governance and orchestration.

# *[DataSphere Studio](https://github.com/WeBankFinTech/DataSphereStudio)* 

**[Click me](https://github.com/WeBankFinTech/DataSphereStudio) to Github repo**

[DataSphere Studio](https://github.com/WeBankFinTech/DataSphereStudio) is positioned as a data application development portal, and the closed loop covers the entire process of data application development. With a unified UI, the workflow-like graphical drag-and-drop development experience meets the entire lifecycle of data application development from data import, desensitization cleaning, data analysis, data mining, quality inspection, visualization, scheduling to data output applications, etc.

# *[Scriptis](https://github.com/WeBankFinTech/Scriptis)*

**[Click me](https://github.com/WeBankFinTech/Scriptis) to Github repo**

[Scriptis](https://github.com/WeBankFinTech/Scriptis) is for interactive data analysis with script development(SQL, Pyspark, HiveQL), task submission(Spark, Hive), UDF, function, resource management and intelligent diagnosis.

# *[Qualitis](https://github.com/WeBankFinTech/Qualitis)* 

**[Click me](https://github.com/WeBankFinTech/Qualitis) to Github repo**

[Qualitis](https://github.com/WeBankFinTech/Qualitis) is a one-stop data quality management platform that supports quality verification, notification, and management for various datasource. It is used to solve various data quality problems caused by data processing.

# *[Schedulis](https://github.com/WeBankFinTech/Schedulis)*

**[Click me](https://github.com/WeBankFinTech/Schedulis) to Github repo**

[Schedulis](https://github.com/WeBankFinTech/Schedulis) is a high performance workflow task scheduling system that supports high availability and multi-tenant financial level features, Linkis computing middleware, and has been integrated into data application development portal DataSphere Studio

# *[Exchangis](https://github.com/WeBankFinTech/Exchangis)*

**[Click me](https://github.com/WeBankFinTech/Exchangis) to Github repo**

[Exchangis](https://github.com/WeBankFinTech/Exchangis) is a lightweight,highly extensible data exchange platform that supports data transmission between structured and unstructured heterogeneous data sources. On the application layer, it has business features such as data permission management and control, high availability of node services and multi-tenant resource isolation. On the data layer, it also has architectural characteristics such as diversified transmission architecture, module plug-in and low coupling of components.

# *[Prophecis](https://github.com/WeBankFinTech/Prophecis)*

**[Click me](https://github.com/WeBankFinTech/Prophecis) to Github repo**

[Prophecis](https://github.com/WeBankFinTech/Prophecis) is a one-stop machine learning platform developed by WeBank. It integrates multiple open-source machine learning frameworks, has the multi tenant management capability of machine learning compute cluster, and provides full stack container deployment and management services for production environment.

# More open-source WDS components? Coming soon...


## WeDataSphere Introduction

WeDataSphere is a financial level one-stop open-source suitcase for big data platforms. The fundamental platform consists of 4 layers for data exchange, data distribution, computation and storage; The functional platform consists of 3 layers for platform tools, data tools and application tools, focusing on the implementations of various user requirements about functional tools. These construct as a complete technical ecosystem of big data platform and provides one-stop sufficient components and functionalities support. 

## WeDataSphere Core Features

- Fundamental capabilities

Powered by miscellaneous open-source components contributed by the community, such as Hadoop, Spark, Hbase, KubeFlow adn FFDL, WeDataSphere achieves financial level reliability on infrastructural data computation, storage and exchange. It also contributes some enhancements to those open-source versions by addressing security, performance, availability and manageability issues in practice with bug fixes. 

- Platform tools

Consists of a platform portal, a data middleware(Linkis) and an operation management system. The platform portal supports product map, financial expense calculation and cloud service application; As a data middleware, Linkis links concrete applications up with underlying computation/storage systems with capabilities of financial level multi-tenant, resource governance and access isolation, filling gaps for the open-source community and the industry; The operation management system encompasses cluster management, configuration management, change management and service request automation, supports one-click installation, one-click upgrade and graphical operation&maintenance, and provides functionalities of alert, health monitoring&diagnosis and automatic recovery, simplifying the operation&maintenance process of the platform.

- Data tools

Consists of data map, data desensitization, data quality and data exchange tools across different Hadoop clusters. Data map manages the universal data resource of the whole bank, with components of meta-data management, data access control, data consanguinity and the on-developing data quality and data model functions. Data desensitization desensitizes highly confidential data and keeps users from accessing it directly. The data quality tool provides a unique process to define and detect the quality of datasets with immediate problem reporting. The data exchange tools across different Hadoop clusters supports the scheduling, monitoring, statistics and management for data exchange tasks.

- Application tools

Consists of the development&exploration tool(Scriptis), a graphical workflow scheduling system, a data visualization BI tool and a machine learning support system. Scriptis connects with various computation/storage engines with graphical interface and multi development languages support. The graphical workflow scheduling system provides a graphical interface for workflow definition, job execution, dependency reveal, status display, historical statistics and monitoring configuration. The data visualization BI tool generates various charts by drag&drop operations and simple scripting, with scheduled email available. The machine learning support system supports multiple model training mode, including both self-developed ML algorithms and open-source ML frameworks, with multi-tenant management alility for high-performance clusters.

## WeDataSphere major Advantages
<br>
![WDSAdvantages](https://github.com/WeBankFinTech/WeDataSphere/blob/master/images/introduction/WDSAdvantages.png)

- One stop

  The 3 layers of platform tools, data tools and application tools plus the powerful machine learning capability, build up an enterprise big data solution.

- Synchronization across clusters among 3 datacenters in 2 cities

  Effecient&reliable big data transportation across clusters/IDCs, with sophisticated data backup and disaster tolerance solutions.

- Financial grade
  
  Unified security control, fully container/microservice adoption and multi-tenant isolation for different layers.

- Seamless expirence
  
  The unique data middleware(Linkis) links up systems in different layers, bringing data consanguinity, code reusability and user resources altogether.
  
- Open source
  
  Core components already open source, the rest coming soon. 

## WeDataSphere Community

If you desire immediate response, please kindly raise issues to us or scan the below QR code by WeChat and QQ to join our group:
<br>
![weChatAndQQ](images/introduction/weChatQQ.png)
