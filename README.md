**Visit [our official web site](http://www.naver.com) for more information and [Latest updates on Pinpoint](http://www.naver.com)**

### Latest Release(2020/09/09)
***
We're happy to announce the release of Pinpoint v2.1.0. Please check the release note at [https://github.com/naver/pinpoint/release/tag/v2.1.0.](https://github.com/naver/pinpoint/releases/tag/v2.1.0)

The current stable version is [v2.1.0](http://www.naver.com)

### Live Demo
***
Take a quick look at PinPoint with our [demo](http://www.naver.com)!

### PHP, PYTHON
***
Pinpoint also supports application written in PHP, Python. Check-out our agent repository.

### About Pinpoint
***

**Pinpoint** is an APM (Application Performance Management) tool for large-scale distributed systems written in Java / [PHP](https://github.com/naver/pinpoint-c-agent)/PYTHON. Inspired by [Dapper](http://research.google.com/pubs/pub36356.html "Google Dapper"), Pinpoint provides a solution to help analyze the overall structure of the system and how components within them are interconnected by tracing transactions across distributed applications.

You should definitely check **Pinpoint** out If you want to

* understand your [application topology](https://www.naver.com) at a glance
* monitor your application in Real-Time
* gain _code-level_ visibility to every transaction
* install APM Agents without changing a single line of code
* have minimal impact on the performance (approximately 3% increase in resource usage)

### Getting Started
* [Quick-start guide](https://naver.github.io/pinpoint/quickstart.html)  for simple test run of Pinpoint
* [Installation guide](https://naver.github.io/pinpoint/installation.html)  for further instructions.

### Overview
***
Services nowadays often consist of many different components, communicating amongst themselves as well as making API calls to external services. How each and every transaction gets executed is often left as a blackbox. Pinpoint traces transaction flows between these components and provides a clear view to identify problem areas and potential bottlenecks.  
For a more intimate guide, please check out our _[Introduction to Pinpoint](http://naver.github.io/pinpoint/#want-a-quick-tour)_ video clip.

*  **ServerMap**  - Understand the topology of any distributed systems by visualizing how their components are interconnected. Clicking on a node reveals details about the component, such as its current status, and transaction count. 
* **Realtime Active Thread Chart** - Monitor active threads inside applications in real-time.
* **Request/Response Scatter Chart** - Visualize request count and response patterns over time to identify potential problems. Transactions can be selected for additional detail by **dragging over the chart**.
*![ss_server-map.png](https://github.com/naver/pinpoint/blob/master/doc/images/ss_server-map.png?raw=true)
**CallStack** - Gain code-level visibility to every transaction in a distributed environment, identifying bottlenecks and points of failure in a single view.
![Call Stack](https://github.com/naver/pinpoint/raw/master/doc/images/ss_call-stack.png)
* **Inspector** - View additional details on the application such as CPU usage, Memory/Garbage Collection, TPS, and JVM arguments.![Inspector](https://github.com/naver/pinpoint/raw/master/doc/images/ss_inspector.png)
### Supported Modules
***
* JDK 6+
* [Tomcat 6/7/8/9/](https://always0ne.github.io/github/Markdown/#%EC%9D%B8%EB%9D%BC%EC%9D%B8-%EC%9D%B8%EC%9A%A9),[Jetty 8/9](https://always0ne.github.io/github/Markdown/#%EC%9D%B8%EB%9D%BC%EC%9D%B8-%EC%9D%B8%EC%9A%A9),etc...
* Spring, Spring Boot (Embedded Tomcat, Jetty, Undertow), GoogleHttpClient, OkHttpClient,
*  Apache HTTP Client 3.x/4.x, JDK HttpConnector, GoogleHttpClient, OkHttpClient, NingAsyncHttpClient, Akka-http, Apache CXF
-   Thrift Client, Thrift Service, DUBBO PROVIDER, DUBBO CONSUMER, GRPC
-   ActiveMQ, RabbitMQ, Kafka
-   MySQL, Oracle, MSSQL(jtds), CUBRID, POSTGRESQL, MARIA
-   Arcus, Memcached, Redis([Jedis](https://github.com/naver/pinpoint/blob/master/plugins/redis),  [Lettuce](https://github.com/naver/pinpoint/tree/master/plugins/redis-lettuce)), CASSANDRA, MongoDB, Hbase, Elasticsearch
-   iBATIS, MyBatis
-   DBCP, DBCP2, HIKARICP, DRUID
-   gson, Jackson, Json Lib, Fastjson
-   log4j, Logback, log4j2

### Compatibility
***
Java version required to run Pinpoint:
|**Pinpoint Version** | **Agent** | **Collector** | ** Web**|
|-----|-----|-----|-----|
|1.5.x|6-8|7-8|7-8|
|-----|-----|-----|-----|
|1.6.x|6-8|7-8|7-8|
|-----|-----|-----|-----|

### Community
***
[Github issues](http://www.naver.com)
[Google group](http://www.naver.com)
[Gitter](http://www.naver.com)

We have Chinese community now, welcome to join!

![QQ Group1](https://github.com/naver/pinpoint/raw/master/doc/images/NAVERPinpoint.png)

### License
***
Pinpoint is licensed under the Apache License
