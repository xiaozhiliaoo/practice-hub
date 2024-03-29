# 我的工程实践，知识管理实践

**Website**: https://xiaozhiliaoo.github.io/practice-hub/

> 持续深入：keep going deep
>
> 构建知识体系：build knowledge system
>
> 复用方案：reuse solution
>
> 新技术学习：new technology learning
>
> 避免重复学习但是没有进步：new technology learning
>
> 快速重捡：relearn fast
>
> 
>
> **`emtpy`**: the repositories is empty
>
> **`prepare`**: the repositories is prepare to publish，not very well
>
> **`recommend`**: the repositories is recommend
>
> **`private`**: you can`t access

# The Big Picture

![](./images/KnowledgeSystem.png)

# The Most Important/Interesting Things

对我来说，值得研究的技术也是我感兴趣有：**软件工程**，**分布式系统**，**数据库**，**编程语言**。非技术的是行业。

[**软件工程**](#software-engineering)：包括软件开发方法学，软件设计与架构，软件库和框架，模式，系统架构，应用架构等。

[**分布式系统**](#computer-science)：包括理论和工业实践，分布式计算，分布式存储，以及各类中间件系统。

**[数据库](#computer-science)**：包括理论和工业实践，MySQL，PostgreSQL等以及分布式数据，云原生数据库等。

**[编程语言](#computer-science)**：包括理论和具体编程语言。

[**行业**](https://github.com/xiaozhiliaoo/commerce-practice):包括开源，商业公司，证券市场，人物，基金会等业内通识。

## Repository Structure(仓库的通用结构)

仓库通用目录结构分为以下格式：

**book**（该技术的相关书籍，slides等信息）

​				--------**slides**(比较好的slides)

**conference**（该技术的行业会议）

**course** （该技术的课程）

**paper** （该技术相关的论文）

**wikipedia** （该技术的维基百科，视频链接，awesome，相关人物，笔记等信息）

​				--------**notes**（自己学习的笔记整理）

**daily** （该技术某一天的学习）

​				--------**yyyy-MM-dd.md**

**code**（该技术相关代码）



## Catalog(目录)

[我的博客](#Blog)

[cloud native](#Cloudnative)

[linux](#Linux)

[language](#Language)

[middleware](#Middleware)

[BigData](#BigData)

[database](#Database)

[infrastructure](#Infrastructure)

[software engineering](#Software-engineering)

[distributed system infrastructure engineering](#Distributed-system-infrastructure-engineering)

[Research](#Research)

[Spring](#Spring)

[interview](#Interview)

[computer science](#Computer-science)  

[others](#Others)

## Blog

- [xiaozhiliao](https://xiaozhiliaoo.github.io/) Focus on technology internals.
- [51cto](https://blog.51cto.com/thinklili) Focus on technology problem solution.

## Cloudnative
- [k8s-practice](https://github.com/xiaozhiliaoo/k8s-practice): rancher,helm,opertor,istio,operate shell,install script,useful cmd
- [docker-practice](https://github.com/xiaozhiliaoo/docker-practice): base env,etcd,redis-sentinel,redis-cluster,mongo replica set,kafka cluster,zk cluster,rabbitmq images **`recommend`**

## Linux
- [linux-practice](https://github.com/xiaozhiliaoo/linux-practice) :system programming(tlpi), bash <font color=green>**`prepare`**</font>
- [shell-practice](https://github.com/xiaozhiliaoo/shell-practice): learning shell. include shell books
- [aupe](https://github.com/xiaozhiliaoo/apue.3e-practice.git) ：learning Advanced Programming in the UNIX Environment, Third Edition
- [lsp](https://github.com/xiaozhiliaoo/lsp-practice) ：learnig Linux System Programming, 2nd Edition

## Language

### Java
- [java-base](https://github.com/xiaozhiliaoo/java-practice): reflect,ref,invoke,jcf,java.lang.util.*
- [effective-java-practice](https://github.com/xiaozhiliaoo/effective-java-practice): effective-java-practice <font color=green>**`recommend`**</font>
- [thinkinginjava-practice](https://github.com/xiaozhiliaoo/thinkinginjava-practice): thinkinginjava code and solution <font color=green>**`recommend`**</font>
- [jvm-practice](https://github.com/xiaozhiliaoo/jvm-practice): understanding jvm
- [concurrency-practice](https://github.com/xiaozhiliaoo/concurrency-practice): juc,disruptor,jcip <font color=green>**`recommend`**</font>
- [pattern-practice](https://github.com/xiaozhiliaoo/pattern-practice):  GOF,POSA,J2EE Pattern，concurrency pattern,idiom。 <font color=green>**`recommend`**</font>
- [refactor-practice](https://github.com/xiaozhiliaoo/refactor-practice): refactor martin fowler
- [websocket-practice](https://github.com/xiaozhiliaoo/websocket-practice): websocket-practice
- [lambda-practice](https://github.com/xiaozhiliaoo/lambda-practice): lambda:java programming in a multicore world
- [animal-shark](https://github.com/xiaozhiliaoo/animal-shark): benchmark test toolkit
- [servlet-practice](https://github.com/xiaozhiliaoo/servlet-practice): servlet-practice
- [cache-practice](https://github.com/xiaozhiliaoo/cache-practice): caffeine,guava,ehcache,spring-cache
- [task-schedule-practice](https://github.com/xiaozhiliaoo/task-schedule-practice): task schedule,spring task,quartz
- [common-practice](https://github.com/xiaozhiliaoo/common-practice): for verify API,and library usage, guava,apache-common...                                                                       
- [jmh-practice](https://github.com/xiaozhiliaoo/jmh-practice): jmh for benchmarks                                                                    
- [java-security-practice](https://github.com/xiaozhiliaoo/java-security-practice): java-security. base64,bouncy castle. commons codec sample
- [mybatis-practice](https://github.com/xiaozhiliaoo/mybatis-practice) learning mybatis

### Golang
- [go-practice](https://github.com/xiaozhiliaoo/go-practice): gopl learing
- [go-probabilistic-ds-practice](https://github.com/xiaozhiliaoo/go-probabilistic-ds-practice): go probabilistic data structure practice
- [go-kv-practice](https://github.com/xiaozhiliaoo/go-kv-practice): embedded kv(leveldb,boltdb)


### Python
- [python-practice](https://github.com/xiaozhiliaoo/python-practice): python-practice


### Javascript
- [javascript-practice](https://github.com/xiaozhiliaoo/javascript-practice): javascript base from miaov course

### Rust

- [rustlings](https://github.com/xiaozhiliaoo/rustlings) pass all game,just for fun.

### NodeJS

[nodejs-practice](https://github.com/xiaozhiliaoo/nodejs-practice) learning NodeJS

## Middleware
- [rpc-practice](https://github.com/xiaozhiliaoo/rpc-practice) rpc trade off and rpc select choice
- [webserver-practice](https://github.com/xiaozhiliaoo/webserver-practice): apache,nginx,haproxy,lvs,varnish,squid 
- [zookeeper-practice](https://github.com/xiaozhiliaoo/zookeeper-practice): zk base,curator,distributed lock,
- [netty-practice](https://github.com/xiaozhiliaoo/netty-practice): io,nio,aio,linux io model,netty-practice
- [mq-practice](https://github.com/xiaozhiliaoo/mq-practice): rabbitmq,rocketmq,activemq <font color=green>**`emtpy`**</font>
- [db-sharding-practice](https://github.com/xiaozhiliaoo/db-sharding-practice): sharding jdbc,shard db and table
- [akka-practice](https://github.com/xiaozhiliaoo/akka-practice) akka learning
- [search-practice](https://github.com/xiaozhiliaoo/search-practice): es，solr，lucene
- [microservice-practice](https://github.com/xiaozhiliaoo/microservice-practice): microservice learning summary.

## BigData

- [storm-practice](https://github.com/xiaozhiliaoo/storm-practice): storm
- [flink-practice](https://github.com/xiaozhiliaoo/flink-practice): flink
- [bigdata](https://github.com/xiaozhiliaoo/bigdata): BigData Basic. Hadoop ecosystem and more.

## Database 

- [mysql-practice](https://github.com/xiaozhiliaoo/mysql-practice): offical doc learn,high performance mysql, innodb iternals
- [data-access-practice](https://github.com/xiaozhiliaoo/data-access-practice): data-access-practice.
- [kv-store-pracitce](https://github.com/xiaozhiliaoo/kv-store-pracitce): redis,riak.
- [cassandra-practice](https://github.com/xiaozhiliaoo/cassandra-practice) cassandra for fun.
- [timeseries-db-practice](https://github.com/xiaozhiliaoo/timeseries-db-practice) time series.
- [document practice](https://github.com/xiaozhiliaoo/document-db-practice) mongodb practice.
- [graphdb practice](https://github.com/xiaozhiliaoo/graph-db-practice.git) graphdb practice.

## Infrastructure

[storage](https://github.com/xiaozhiliaoo/storage-infra-practice): storage system: filesystem,object storage,block storage and hardware,disk

[network](https://github.com/xiaozhiliaoo/network-infra-practice): DPDK , OpenFlow....

[compute](https://github.com/xiaozhiliaoo/compute-infra-practice): **`empty`**

## Software-engineering
- [software-engineering](https://github.com/xiaozhiliaoo/software-engineering-practice) course paper book
- [performance-practice](https://github.com/xiaozhiliaoo/performance-practice) arthas, Brendan Gregg, perf,load,cpu,io,
- [develop-tools-practice](https://github.com/xiaozhiliaoo/develop-tools-practice) idea,git,eclipse,vim,makefile 
- [architecture-practice](https://github.com/xiaozhiliaoo/architecture-practice) design principle,ood, ddd, code smell,design smell,clean architecture, patterns,book,agile develop,xp,microservice architecture, distributed architecture, cloud native architecture.
- [project-management-practice](https://github.com/xiaozhiliaoo/project-management-practice.git) <font color=green>**`emtpy`**</font> project management see, think, compare
- [@Refactor](https://github.com/xiaozhiliaoo/refactor) @Refactor annotation to record design smell and code smell.
- [cicd-practice](https://github.com/xiaozhiliaoo/cicd-practice): jenkins,gitlab,pipeline two books: 《持续集成：软件质量改进和风险降低之道》 《持续交付：发布可靠软件的系统方法》
  - [test-practice](https://github.com/xiaozhiliaoo/test-practice):    Focus on **continous test** phase of continuous integration. unit test, benchmark test, junit5, hamcrest, easymock 
  - [spring-test-practice](https://github.com/xiaozhiliaoo/spring-test-practice) Focus on spring style project test. include Spring Test and Spring Boot Test
  - [continuous-inspection-practice](https://github.com/xiaozhiliaoo/continuous-inspection-practice) Focus on **continous inspection** phase of continuous integration. sonar in action,code static analysis, p3c,sonar lint practice,findBugs.bug patterns. improve code,design quality

## Distributed-system-infrastructure-engineering
- Observability
  - [tracing-practice](https://github.com/xiaozhiliaoo/tracing-practice) distributed tracing dapper,sleuth
  - [logging-practice](https://github.com/xiaozhiliaoo/logging-practice)  common logging with inotify, chukwa, FileBeat, fluentd, syslog , logstash, alibaba sls.
  - [monitoring-pracitce](https://github.com/xiaozhiliaoo/monitoring-practice.git) prometheus, springboot-admin
- [distributed-transaction-practice](https://github.com/xiaozhiliaoo/distributed-transaction-practice.git) seata, mq trancaction..
- [distributed-scheduling-practice](https://github.com/xiaozhiliaoo/distributed-scheduling-practice) cluster scheduler architectures,yarn,mesos,borg,omega....
- [etcd-raft](https://github.com/xiaozhiliaoo/etcd-raft) etcd raft standalone
- [etcd-raftexample](https://github.com/xiaozhiliaoo/etcd-raftexample) etcd raftexample standalone


## Research
- [commerce-practice](https://github.com/xiaozhiliaoo/commerce-practice) commerce history，company，person，industry，opensource，foundation，stock market，investment.


## Spring
- [interface21](https://github.com/xiaozhiliaoo/interface21): interface21 Rod Johnson:j2ee development without ejb, j2ee design and development <font color=green>**`recommend`**</font>
- [ioc-practice](https://github.com/xiaozhiliaoo/ioc-practice): ioc include:picocontainer,guice,spring ioc...
- [spring-project-skeleton](https://github.com/xiaozhiliaoo/spring-project-skeleton) fast develop spring project(spring+springmvc+mybatis)
- [spring-practice](https://github.com/xiaozhiliaoo/spring-practice) spring learning.

## Interview
- [interviews](https://github.com/xiaozhiliaoo/interviews) : interview prepare,leet&lint code,system design,work experience,project experience <font color=green>**`private`**</font>
- [my-resume](https://github.com/xiaozhiliaoo/my-resume) my resume **`empty`**


## Computer-science
Focus on classic computers science course.

- [distributed-practice](https://github.com/xiaozhiliaoo/distributed-practice): distributed system       
- [database-system-practice](https://github.com/xiaozhiliaoo/database-system-practice) database-system-practice
- [operating-system-practice](https://github.com/xiaozhiliaoo/operating-system-practice) operating-system-practice
- [compliers-practice](https://github.com/xiaozhiliaoo/compliers-practice) compliers-practice
- [programming-language](https://github.com/xiaozhiliaoo/programming-language) PL learning
- [algorithm-practice](https://github.com/xiaozhiliaoo/algorithm-practice): data structure and algorithm,Algorithms by Robert Sedgewick,not leetcode
- [computer-system-practice](https://github.com/xiaozhiliaoo/computer-system-practice) computer architecture practice
- [network-practice](https://github.com/xiaozhiliaoo/network-practice) network practice

## Others
- [reading-note](https://github.com/xiaozhiliaoo/reading-note): reading-notes
- [meetup](https://github.com/xiaozhiliaoo/meetup.git): meetings I participated in.
- [translate](https://github.com/xiaozhiliaoo/translate-practice.git) : book translate and more...
- [my-collect](https://github.com/xiaozhiliaoo/my-collect) my collect about book,paper,slides,video,meeting,conference
- [monitor-base](https://github.com/xiaozhiliaoo/monitor-base.git) blog:https://blog.51cto.com/thinklili/2360858