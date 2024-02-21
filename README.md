
# Zhang Han

**Zhang Han | Male | Born in August 1994 | Bachelor's Degree | 5 years of work experience | Guangzhou**  
**Education: Jinan University, Internet of Things Engineering, Full-time Bachelor, Bachelor of Engineering, September 2012 - June 2017**  
Phone: 18022118521, Email: [fancydick@163.com](fancydick@163.com)  

## Professional Skills  

- Proficient in Java language, with good enterprise-level programming habits; has a deep understanding of the collection classes, IO streams, and concurrent programming source code in Java, and has practical experience in using thread pools and solving thread safety issues in actual development.
- Understands the memory model in JVM, familiar with the commonly used garbage collectors in JVM, and has online tuning experience.
- Has used MySQL, Oracle, and other relational databases in enterprise-level development, as well as used domestic databases Kingbase and GaussDB. Has experience in data structure optimization and slow query optimization in the production environment.
- Can proficiently use Redis, MongoDB and other non-relational databases in enterprise-level development, and has solutions to extreme problems encountered in the use of Redis such as cache avalanche and penetration.
- Has many years of SSM framework development experience, and can also proficiently use the SpringBoot framework; has a deep understanding of the source code of the SpringBoot automatic assembly principle, startup process, etc.; has experience in using the SSM framework to build backend services.
- Understands the principle of AOP dynamic proxy, and has experience in aspect-oriented programming development.
- Has enterprise-level usage experience of multiple components in SpringCloud. For example: Nacos, OpenFeign, Gateway, Sentinel and other components.
- Has used kafka and RabbitMQ message middleware in production, familiar with the orderliness, reliability, idempotence of messages and the implementation principle of its transactions.
- Proficient in English, with a certain ability to read and translate English documents.
- Proficient in using the idea development tool.

## Work Experience

### November 2019 - July 2023 | Guangzhou Nahai Chuan Internet Technology Co., Ltd. | 100-200 people | Backend Development Engineer

The first phase of the Dongguan Municipal Government Data Brain project includes "One Lake and Four Platforms" (Distributed Data Lake, Big Data Basic Support Platform, Data Convergence Platform, Data Governance Platform, Data Service Platform), which is committed to building the city's digital government data base. Except for the big data basic support platform for purchasing Huawei's FusionInsight (similar to open source Ambari), others are independently developed.
During the implementation of the project, according to the actual needs of data work, the architecture of [One Lake and Four Platforms] evolved into a [Distributed Data Lake] architecture. Each bureau deploys a data lake sub-lake, responsible for the management of the bureau's data life cycle (collection, storage, governance, and use), and the municipal government deploys the data lake main lake, responsible for the panoramic analysis and display of the city's data, and the application and approval of data rights.

#### Data Convergence

1. Each bureau builds a real-time backup library for 2000 business systems.
2. Build a data convergence platform, integrate multiple ETL tools, aggregate heterogeneous data from various systems, and uniformly converge to the data warehouse. It is necessary to redesign the synchronization program for various data sources, such as DB2, oracle, mysql, kingbase, etc.
3. Due to the different construction time and environment of each business system, and the special security requirements of the government network, it is also necessary to clarify the network environment between systems, communicate with the operation and maintenance personnel of each system and open the connection, and implement safe and effective data transmission.

Technology Stack
- Oracle, MySql, GaussDB, Postgre, Kettle, DataX

#### Data Service Platform

Develop a data service platform based on the data warehouse. Mainly responsible for the construction of users and organizational systems, the development of a visual metadata management platform, and the realization of data sharing and data permission control.

Technology Stack
- SSM, GuassDB, Redis, MyBatis, JPA, RabbitMq, Minio, Kafka, Nacos

#### Bureau Business System

1. Review the specific requirements of the bureau with the product manager and provide the implementation plan.
2. Investigate the old system of the bureau, sort out the business data of the old system, develop data conversion scripts, and realize database localization.
3. Dock with the data service platform, get data from the DM data supermarket, and establish ADS layer application data.
4. Build backend basic services.
5. Designed the user organization system structure.
6. Develop a business system based on application data, realize business logic, realize cross-bureau business data application, analysis and display,

Technology Stack
- Spring, Kingbase, Mysql, Redis, MyBatis, JPA, RabbitMq, Minio

#### Epidemic Big Screen Development

The new crown epidemic that started in 2020 is a practice of data convergence, data governance, and data application. In the early stage of the epidemic, the data convergence work was extremely difficult. According to the table data reported by each grid, use python and other scripting languages to extract data, perform a large amount of data cleaning and complete the import work, and establish an epidemic basic data warehouse. In the subsequent system development, abstract various indicators, establish a model covering multiple dimensions such as time, geographical location, and population, and form an epidemic theme library. Based on the multi-dimensional model, perform comparison, trend, and correlation analysis, output the results to the wisdom big screen, and provide more effective decision-making assistance.

Technology Stack
- Python, SSM, Redis, MInio

### March 2018 - November 2019 | Guangzhou Huidian Yunlian Internet Technology Co., Ltd. | 100-200 people | Backend Development Engineer

Electricity spot simulation competition system, in the background where the electricity spot market has not yet started and the relevant rules are still blank, according to the initial rules of the Guangdong electricity spot market to design a simulation system, used for pre-market talent training in the electricity spot market.
According to the massive data of Southern Power Grid nodes, lines, tides, sections, and West-to-East power transmission, using operations optimization, artificial intelligence and other algorithms, to predict the price of each billing node participating in the spot market, solving the balance of quantity and price in the spot environment. Functions include basic surface analysis and decision cockpit.

#### Electricity Spot Simulation Competition System

1. Review the design requirements with the product manager in the early stage and provide the implementation plan.
2. Assist the architect to build the basic architecture of the system, use the spring framework and restful interface style, and be responsible for the business logic and data model design and development of some modules.
3. Data collection and database design, through interfaces, mirror libraries and other methods, all the electricity user data of third-party companies (Foshan Eagle Eye Technology) are converged to the simulation platform, and cleaned and governed to meet the needs of the load prediction team.
4. Responsible for the technical document translation of the Australian team's electricity market simulation engine, and the data interaction implementation between the competition system and the engine. Optimized the interaction between the system and the spot simulation service, improving the stability of the service.
5. As the system runs, it encounters the problem of long-term query of massive power grid data, and uses HBase to offline data and Hive to aggregate queries.
1. Cooperate with the architecture group to perform stress testing and optimize high concurrency. Adjust the GC strategy of JVM to alleviate the memory overflow problem during high concurrency of the service.

Technology Stack
- SSM, Oracle, Redis, JPA, Kafka, FTP

#### 2017.3-2017.6 | 广州迅易科技有限公司 | 100-200人 | 数据开发实习生

数据运维

1. 数据导入、导出。
2. Oracle数据库运营维护。

## 其他

1. 待人处事随和，兴趣爱好丰富，善于调整自己的状态更好适应工作。
1. 喜欢与有目标、有能力的人为友，希望在目标明确、积极向上的团队中工作。
1. 热爱IT行业，对新兴事物抱有好奇心，虚心好学 。
1. 工作中能够有效的沟通以尽快达到交流的目的。
1. 爱好：体育运动、音乐、绘画、摄影。
特长：游泳、篮球、足球。
1. 2017.5-2017.12 参加雅思考试两次，两次均分分别为6和7，能熟练阅读英文文档。同时期，申请并获得澳洲阿德莱德大学、悉尼大学、悉尼科技大学的硕士课程预录取通知书，由于个人原因没有继续出国留学计划