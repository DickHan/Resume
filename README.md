# 张涵的简历

**张涵 | 男 | 1994.08 | 本科 | 5年工作经验 | 广州**  
**教育经历：暨南大学，物联网工程，全日制本科，工学学士学位，2012.09～2017.06**  
电话：18022118521，邮箱：[fancydick@163.com](fancydick@163.com)  

## 专业技能  

-	熟练掌握Java语言，具备良好的企业级编程习惯；对Java语言中的集合类、IO流、并发编程底层源码有过深入研究，在实际开发中有使用线程池并解决线程安全问题的实战经验。
-	理解JVM中的内存模型，熟悉JVM中的常用垃圾回收器，同时有过线上调优经验。
-	在企业级开发中使用过MySQL、Oracle、等关系型数据库，以及使用过国产数据库Kingbase和GaussDB。有数据结构优化经验和生产环境慢查询优化经验。
-	能够在企业级开发中熟练使用Redis、MongoDB等非关系型数据库，有解决Redis在使用过程中遇到的极端问题比如缓存雪崩、穿透等问题的方案。
-	有多年的SSM框架开发经验，同时也能熟练使用SpringBoot框架；对于SpringBoot自动装配原理、启动流程等源码有过深入理解；有使用SSM框架搭建后端服务的经验。
-  理解AOP动态代理的原理，掌握面向切面的编程开发经验。
-	对于SpringCloud中的多个组件也有企业级使用经验。例如：Nacos、OpenFeign、Gateway、Sentinel等组件。
-	在生产中使用过kafka和RabbitMQ消息中间件，熟悉消息的顺序性，可靠性，幂等性以及它事务的实现原理。
-	熟练掌握英语，有一定的英文文档阅读和翻译能力。
-	熟练使用idea开发工具。


## 工作经历

### 2019.11-2023.7 |广州市纳海川互联网科技有限公司 | 100-200人 | 后端开发工程师

东莞市政府数据大脑一期项目包含“一湖四平台”(分布式数据湖、大数据基础支撑平台、数据汇聚平台、数据治理平台、数据服务平台)，致力于打造市数字政府数据基础底座。除了大数据基础支撑平台为采购华为的 FusionInsight(类似于开源的Ambari)外，其他为自主研发。
项目在实施过程中，根据数据工作实际的需要，从中心化的[一湖四平台]架构演进成[分布式数据湖]架构。各委办局部署一个数据湖子湖，负责委办局数据生命周期(采存治管用)管理，市政府部署数据湖主湖，负责全市数据的全景分析和展示，以及用数权限的申请审批。 


#### 数据汇聚


1.  各委办局2000个业务系统建设实时备库。
2.  建设数据汇聚平台，整合多种ETL工具，将各系统异构数据作聚合，统一汇聚到数据仓库。其中需要针对各种数据源，如DB2、oracle、mysql、kingbase等重新设计同步程序。
3.  由于各个业务系统的建设时间和环境不同，以及政务网的特殊安全要求，还需要理清系统之间的网络环境，与各个系统的运维人员沟通并打通连接，实施安全有效的数据传输。


技术栈
- Oracle、MySql、GaussDB、Postgre、Kettle、DataX

#### 数据服务平台


基于数据仓库开发数据服务平台。主要负责用户、组织机构体系构建，开发可视化的元数据管理平台，实现数据共享和数据权限控制。


技术栈
- SSM、GuassDB、Redis、MyBatis、JPA、RabbitMq、Minio、Kafka、Nacos

#### 委办局业务系统



1.  委办局具体需求评审，提供实现方案。
2.  委办局旧系统调研，整理旧系统业务数据，开发数据转化脚本，实现数据库国产化。
3.  对接数据服务平台，从DM数据超市获取数据，建立ADS层应用数据。
4.  搭建后端基础服务。
5.  设计了用户组织体系结构。
6.  基于应用数据开发业务系统，实现业务逻辑，实现跨局的业务数据应用、分析以及展示，


技术栈
- Spring、Kingbase、Mysql、Redis、MyBatis、JPA、RabbitMq、Minio

#### 疫情大屏开发

2020年开始的新冠疫情，是一次数据汇聚、数据治理和数据应用的实践。疫情初期，数据汇聚工作异常艰巨，根据各个网格上报的表格数据，使用python等脚本语言提取数据、进行大量的数据清洗并完成导入工作，建立起疫情基础数据仓库。在后续系统开发中，抽象出各种指标，建立涵盖时间、地理位置、人群等多个维度的模型，形成疫情主题库。基于多维度的模型，进行对比、趋势和关联分析，输出结果到智慧大屏上，提供更有效的决策辅助。

技术栈
- Python、SSM、Redis、MInio

### 2018.3-2019.11 | 广州市汇电云联互联网科技有限公司 | 100-200人 | 后端开发工程师


电力现货模拟竞赛系统，在电力现货市场仍未启动，相关规则仍是空白的背景下，根据广东电力现货市场初期规则设计模拟系统，用于电力现货市场前期人才培训。
根据南方电网节点、线路、潮流、断面、西电东送等海量数据，运用运筹优化、人工智能等算法、实现对每个计费节点的参与现货市场的价格进行预测，解决了现货环境中量价关系的平衡。功能包括基本面分析，决策驾驶舱。

#### 电力现货模拟竞赛系统

1. 前期与产品经理一起评审设计需求，提供的实现方案。
2. 协助架构师，搭建系统基本架构，使用到spring framework、restful接口风格，负责了部分模块的业务逻辑和数据模型设计与开发。
3. 数据归集和数据库设计，通过接口、镜像库等方式，将第三方公司（佛山鹰视科技）的用电用户数据全部汇聚到仿真平台，并进行清洗治理以达到负荷预测小组的需求。
4. 负责澳洲团队电力市场仿真引擎的技术文档翻译，以及竞赛系统和引擎的数据交互实现。优化了系统与现货仿真服务的交互，提高了服务稳定性。
5. 随着系统运行，遇到长期的海量电网数据的查询问题，使用HBase对数据进行离线，Hive聚合查询。
1. 配合架构组进行压力测试，调优高并发情况。调整JVM的GC策略，减缓服务高并发时的内存溢出问题。

技术栈
- SSM、Oracle、Redis、JPA、Kafka、FTP

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
1. 2017.5-2017.12 参加雅思考试两次，两次均分分别为6和7，能熟练阅读英文文档。同时期，申请并获得澳洲阿德莱德大学、悉尼大学、悉尼科技大学的硕士课程预录取通知书，由于个人原因没有继续出国留学计划。