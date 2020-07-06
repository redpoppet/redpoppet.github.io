---
title: <center><h1>苏成龙</h1></center>
date: 2019-05-18 16:03:36
type: about
---

 <!-- <left>
     <h1>苏成龙&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; &emsp;&emsp;&emsp;Python工程师 </h1>
 </left> -->
---
## 个人信息 

* 性 别：男 &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp; 年 龄：28  
* 手 机：15268393382 &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&ensp;  邮 箱：Chenglong.Su1991@gmail.com  
*  blog:&emsp;redpoppet.github.io &emsp;&emsp;&emsp;&emsp; github: https://github.com/redpoppet 
---
## 教育经历

      
* 宁波大学  &emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;2014.9~2017.7&emsp;&emsp;&emsp;&emsp; 计算机应用技术 &emsp;&emsp;  研究生         
* 安徽师范大学&emsp;&emsp;&emsp;&emsp;&emsp; 2010.9~2014.7&emsp;&emsp;&emsp;&emsp;计算机科学与技术 &emsp; 本科  

---


# 工作经历
（工作经历按逆序排列，最新的在最前边，按公司做一级分组，公司内按二级分组）

## 杭州览众数据科技有限公司 （ 2017年2月 ~ 至今 ）

### 供应链智能决策引擎V1.0 ~ V2.0   python工程师 2017.2 -2017.7
作为Python工程师，设计了产品的第一代框架和第二代框架，参与库存优化模型和需求预测模型的开发，性能优化等.

第一代框架主要采用前后端分离，采用mysql作为数据存储。业务模块包括库存优化和需求预测模块。

第二代架构修改为使用Postgresql作为数据存储，增加用户管理系统，精简业务模块。

基于引擎V2.0,支持十几家客户的poc工作，负责带领团队处理所有客户数据导入，模型验证和结果报告输出。

### 大华库存优化项目  技术leader  2017.7 - 2018.3 
为了完善引擎的业务场景，作为标杆客户项目的技术leader，基于数据量级和项目需求，设计了基于ETL和T+1模型决策的系统架构。

指导相关数据仓库建设，负责网站性能提升，把控开发进度，对接客户技术等内容，实现项目一期成功上线。

### 库存优化产品V3.0~V5.0  技术负责人   2018.4 - 2018.8 

基于大华库存优化项目，设计了库存优化产品的第三代，第四代，第五代系统架构, 配合售前进行部分商业活动。

第三代体系架构对大华的系统架构进行了精简，基于kettle完善了etl过程。

第四代体系架构postgresql为Greenplum，数据支持多租户，添加了前台系统，租户后台系统，管理后台系统三层架构。

第五代体系架构增加了开发流程CI/CD流程，实现本地化部署与升级脚本自动化，重构模型代码，使得模型效能提升50%以上。


### 模型工程化组组长   2018.8 - 2020.06 

带领团队对公司的三条产品线(制造，服装，零售)的模型进行改造，进行并行化处理和代码架构调整。通过多种并行方法将cpu利用率提升到100%，内存利用率提升到80%左右。调整三条产品线的模型的代码结构，对数据加载，特征处理，模型优化，结果存储，异常调试等功能进行了标准化，大大提高了模型的开发效率和迁移复用效率。

在此期间，支持模型将数据源从pg迁移至Greenplum，再至Hive，最终将模型迁移至CDH集群运行，基于airflow完成所有模型任务的按序调度。

负责所有项目和产品的模型错误处理工作，模型性能优化工作，模型输入输出规范，输出结果的频率与覆盖问题。

将模型的主线研发，项目迁移与二次开发，性能调优，测试和上线等步骤打造成模型开发体系和标准流程，实现开发，测试和生产三套环境的模型相关的无缝衔接。



### 算法平台组组长   2020.8 - 2020.06 
公司推出了SaaS平台，为了提升模型的开发效率，代码复用率和客制化灵活性，研究了模型组件库，分为应用层，业务单元层，组件层和基础层，通过继承和多态，模块动态加载实现复用和客制，并添加了参数校验，代码加密，部署自动化，求解器封装等模块。

支持模型中心的开发，作为SaaS微服务架构的一部分，提供模型实例管理，模型运算服务化等功能。

迁移模型计算任务到新搭建的模型集群，并设计了一套模型资源便利扩展的机制，支撑业务量快速增长。修改模型运行方式从local升级到cluster模式(包括机器学习类模型和整数规划类模型)，提供队列隔离和资源控制功能，有序使用集群资源。




### 项目辅导   2019.06 - 2020.01

负责公司所有服装产品线的项目实施细节辅导工作，基于项目计划，周上线清单，redmine每日任务，每日展会，每周周会，每周访谈，项目难点定向解决等手段对项目中的需求理解，计划制定，方案评审，开发测试，上线回归等工作进行明确划分和严格规定，促使上线规范率提升一倍以上，项目异常频率降低两倍以上。年终核算平均人效提升两倍。

 

# 开源项目和作品
（这一段用于放置工作以外的、可证明你的能力的材料）

## 开源项目
（对于程序员来讲，没有什么比Show me the code能有说服力了）

 - [STU](http://github.com/yourname/projectname)：项目的简要说明，Star和Fork数多的可以注明
 - [WXYZ](http://github.com/yourname/projectname)：项目的简要说明，Star和Fork数多的可以注明

## 技术文章
（挑选你写作或翻译的技术文章，好的文章可以从侧面证实你的表达和沟通能力，也帮助招聘方更了解你）

- [一个产品经理眼中的云计算：前生今世和未来](http://get.jobdeer.com/706.get)
- [来自HeroKu的HTTP API 设计指南(翻译文章)](http://get.jobdeer.com/343.get) （ ```好的翻译文章可以侧证你对英文技术文档的阅读能力```）

## 演讲和讲义
（放置你代表公司在一些技术会议上做过的演讲，以及你在公司分享时制作的讲义）

  - 2014架构师大会演讲：[如何通过Docker优化内部开发](http://jobdeer.com)
 - 9月公司内部分享：[云计算的前生今世](http://jobdeer.com)

# 技能清单
（我一般主张将技能清单写入到工作经历里边去。不过很难完整，所以有这么一段也不错）

以下均为我熟练使用的技能

- Web开发：PHP/Hack/Node
- Web框架：ThinkPHP/Yaf/Yii/Lavaral/LazyPHP
- 前端框架：Bootstrap/AngularJS/EmberJS/HTML5/Cocos2dJS/ionic
- 前端工具：Bower/Gulp/SaSS/LeSS/PhoneGap
- 数据库相关：MySQL/PgSQL/PDO/SQLite
- 版本管理、文档和自动化部署工具：Svn/Git/PHPDoc/Phing/Composer
- 单元测试：PHPUnit/SimpleTest/Qunit
- 云和开放平台：SAE/BAE/AWS/微博开放平台/微信应用开发

## 参考技能关键字

本技能关键字列表是从最近招聘架构师的数百份JD中统计出来的，括号中是出现的词频。如果你的简历要投递给有机器（简历分选系统）和不如机器（不懂技术的HR）筛选简历环节的地方，请一定从下边高频关键词中选择5～10个适合你自己的。

- java(364)
- web(219)
- mysql(186)
- linux(159)
- php(133)
- oracle(109)
- j2ee(109)
- spring(101)
- sql(95)
- uml(83)
- android(74)
- javascript(68)
- html(62)
- css(59)
- soa(57)
- ajax(57)
- hadoop(54)
- hibernate(54)
- ios(50)
- nosql(48)
- mvc(47)
- jquery(47)
- struts(46)
- tomcat(44)
- python(42)
- xml(39)
- ibatis(38)
- redis(38)
- tcp(36)
- unix(36)
- oop(35)
- html5(34)
- jboss(29)
- hbase(28)
- js(28)
- rose(28)
- websphere(25)
- sqlserver(25)
- memcached(24)
- mongodb(24)
- json(23)
- shell(22)
- nginx(22)
- crm(22)
- weblogic(22)
- apache(19)
- webservice(19)
- jsp(18)
- erp(18)
- ooa(17)
- memcache(16)
- javaee(15)
- lucene(14)
- windows(14)
- ssh(13)
- saas(13)
- powerdesigner(13)
- bi(13)
- aop(12)
- mq(12)
- cache(12)
- asp(12)
- service(12)
- struts2(12)
- jvm(12)
- hive(12)
- lamp(12)
- framework(12)
- mybatis(11)
- db2(11)
- review(11)
- css3(11)
- openstack(11)
- servlet(10)
- ejb(10)
- amp(10)
- rational(10)
- socket(10)
- oo(9)
- jms(9)
- b2c(9)
- o2o(9)
- svn(9)
- lnmp(8)
- jdbc(8)
- div(8)
- springmvc(8)
- mapreduce(8)
- xhtml(8)
- junit(8)
- esb(8)
- db(8)
- eclipse(8)
- api(8)
- ext(8)
- cms(7)
- netty(7)
- jetty(7)
- ioc(7)
- orm(7)
- ui(7)
- yui(6)
- mina(6)
- osgi(6)
- activemq(6)
- ruby(6)
- visio(6)
- node(6)
- vmware(6)
- pc(6)
- yii(5)
- maven(5)
---

# 致谢
感谢您花时间阅读我的简历，期待能有机会和您共事。


