# practice-hub(我的工程实践)
> my practice hub: keep going deep(持续深入)，build knowledge system(构建知识体系)，
> reuse solution(复用方案)，new technology learning(新技术学习)，avoid repeated learning but no progress(避免重复学习但是没有进步)，
> relearn fast(快速重捡)
>
> **project status: 77 projects**
>
> **`emtpy`**: the repositories is empty
>
> **`prepare`**: the repositories is prepare to publish，not very well
>
> **`recommend`**: the repositories is recommend
>
> **`private`**: you can`t access
>
> **`blank`**: not classification

# The most important/interesting things

对我来说，值得研究的技术也是我感兴趣有：**软件设计与架构**，**分布式系统**，**数据库**，**编程语言**。

**软件设计与架构**：包括模式，系统架构，应用架构等。

**分布式系统**：包括理论和工业实践，分布式计算，分布式存储，以及各类中间件系统。

**数据库**：包括理论和工业实践，MySQL，PostgreSQL等以及分布式数据，云原生数据库等。

**编程语言**：包括理论和具体编程语言。

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

[我的博客](#blog)

[cloud native](#cloudnative)

[linux](#linux)

[collect](#collect)

[language](#language)

[middleware](#middleware)

[BigData](#BigData)

[database](#database)

[software engineering](#software-engineering)

[distributed system infrastructure engineering](#distributed-system-infrastructure-engineering)

[Research](#Research)

[Spring](#Spring)

[interview](#interview)

[source code reading](#sourceCode-reading)

[computer science](#computer-science)  CS七剑，计算机七门学科，最重要的七门课。

[notes](#notes)



## blog

- [xiaozhiliao](https://xiaozhiliaoo.github.io/) Focus on technology internals.
- [51cto](https://blog.51cto.com/thinklili) Focus on technology problem solution.

## cloudnative
- [k8s-practice](https://github.com/xiaozhiliaoo/k8s-practice): rancher,helm,opertor,istio,operate shell,install script,useful cmd
- [docker-practice](https://github.com/xiaozhiliaoo/docker-practice): base env,etcd,redis-sentinel,redis-cluster,mongo replica set,kafka cluster,zk cluster,rabbitmq images **`recommend`**

## linux
- [linux-practice](https://github.com/xiaozhiliaoo/linux-practice):system programming(tlpi), bash <font color=green>**`prepare`**</font>
- [shell-practice](https://github.com/xiaozhiliaoo/shell-practice): learning shell. include shell books
- [aupe](https://github.com/xiaozhiliaoo/apue.3e-practice.git) ：learning Advanced Programming in the UNIX Environment, Third Edition
- [lsp](https://github.com/xiaozhiliaoo/lsp-practice)：learnig Linux System Programming, 2nd Edition


## collect
- [my-collect](https://github.com/xiaozhiliaoo/my-collect) my collect about book,paper,slides,video,meeting,conference


## language

### Java
- [java-base](https://github.com/xiaozhiliaoo/java-base-practice): reflect,ref,invoke,jcf,java.lang.util.*
- [thinkinginjava-practice](https://github.com/xiaozhiliaoo/thinkinginjava-practice): thinkinginjava code and solution <font color=green>**`recommend`**</font>
- [pattern-practice](https://github.com/xiaozhiliaoo/pattern-practice):  GOF,POSA,J2EE Pattern，concurrency pattern,idiom。 <font color=green>**`recommend`**</font>
- [refactor-practice](https://github.com/xiaozhiliaoo/refactor-practice): refactor martin fowler
- [websocket-practice](https://github.com/xiaozhiliaoo/websocket-practice): websocket-practice
- [lambda-practice](https://github.com/xiaozhiliaoo/lambda-practice): lambda:java programming in a multicore world
- [tdd-practice](https://github.com/xiaozhiliaoo/tdd-practice): tdd from keck beck
- [animal-shark](https://github.com/xiaozhiliaoo/animal-shark): benchmark test toolkit
- [servlet-practice](https://github.com/xiaozhiliaoo/servlet-practice): servlet-practice
- [jdk-practice](https://github.com/xiaozhiliaoo/jdk-practice): jdk source code read, understand,design **`emtpy`**                                                             
- [cache-practice](https://github.com/xiaozhiliaoo/cache-practice): caffeine,guava,ehcache,spring-cache
- [task-schedule-practice](https://github.com/xiaozhiliaoo/task-schedule-practice): task schedule,spring task,quartz
- [j2ee-practice](https://github.com/xiaozhiliaoo/j2ee-practice): Rod Johnson:j2ee development without ejb, j2ee design and development
- [common-practice](https://github.com/xiaozhiliaoo/common-practice): for verify API,and library usage, guava,apache-common...                                                                       
- [effective-java-practice](https://github.com/xiaozhiliaoo/effective-java-practice): effective-java-practice <font color=green>**`recommend`**</font>
- [jvm-practice](https://github.com/xiaozhiliaoo/jvm-practice): understanding jvm
- [j2eepattern-practice](https://github.com/xiaozhiliaoo/j2eepattern-practice): Core J2EE Patterns: Best Practices and Design Strategies
- [poeaa-practice](https://github.com/xiaozhiliaoo/poeaa-practice): poeaa
- [concurrency-practice](https://github.com/xiaozhiliaoo/concurrency-practice): juc,disruptor,jcip <font color=green>**`recommend`**</font>
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



## middleware
- [rpc-practice](https://github.com/xiaozhiliaoo/rpc-practice) rpc trade off and rpc select choice
- [nginx-practice](https://github.com/xiaozhiliaoo/nginx-practice): nginx,haproxy
- [zookeeper-practice](https://github.com/xiaozhiliaoo/zookeeper-practice): zk base,curator,distributed lock,
- [netty-practice](https://github.com/xiaozhiliaoo/netty-practice): io,nio,aio,linux io model,netty-practice
- [mq-practice](https://github.com/xiaozhiliaoo/mq-practice): rabbitmq,rocketmq,activemq <font color=green>**`emtpy`**</font>
- [kv-store-pracitce](https://github.com/xiaozhiliaoo/kv-store-pracitce): redis,riak...
- [sharding-practice](https://github.com/xiaozhiliaoo/sharding-practice): sharding jdbc,shard db and table
- [akka-practice](https://github.com/xiaozhiliaoo/akka-practice) akka learning
- [search-practice](https://github.com/xiaozhiliaoo/search-practice): es，solr，lucene
- [microservice-practice](https://github.com/xiaozhiliaoo/microservice-practice): microservice learning summary.

## BigData

- [storm-practice](https://github.com/xiaozhiliaoo/storm-practice): storm
- [flink-practice](https://github.com/xiaozhiliaoo/flink-practice): flink
- [bigdata](https://github.com/xiaozhiliaoo/bigdata): BigData basic.

## database 

- [mysql-practice](https://github.com/xiaozhiliaoo/mysql-practice): offical doc learn,high performance mysql, innodb iternals
- [data-access-practice](https://github.com/xiaozhiliaoo/data-access-practice): data-access-practice

## software-engineering
- [performance-practice](https://github.com/xiaozhiliaoo/performance-practice) arthas, Brendan Gregg, perf,load,cpu,io,
- [develop-tools-practice](https://github.com/xiaozhiliaoo/develop-tools-practice) idea,git,eclipse,vim,makefile 
- [architecture-practice](https://github.com/xiaozhiliaoo/architecture-practice) design principle,ood, ddd, code smell,design smell,clean architecture, patterns,book,agile develop,xp,microservice architecture, distributed architecture, cloud native architecture.
- [project-management-practice](https://github.com/xiaozhiliaoo/project-management-practice.git) <font color=green>**`emtpy`**</font> project management see, think, compare
- [spring-project-skeleton](https://github.com/xiaozhiliaoo/spring-project-skeleton) fast develop spring project(spring+springmvc+mybatis)
- [@Refactor](https://github.com/xiaozhiliaoo/refactor) @Refactor annotation to record design smell and code smell.
- [cicd-practice](https://github.com/xiaozhiliaoo/cicd-practice): jenkins,gitlab,pipeline two books: 《持续集成：软件质量改进和风险降低之道》 《持续交付：发布可靠软件的系统方法》
  - [test-practice](https://github.com/xiaozhiliaoo/test-practice):    Focus on **continous test** phase of continuous integration. unit test, benchmark test, junit5, hamcrest, easymock 
  - [spring-test-practice](https://github.com/xiaozhiliaoo/spring-test-practice) Focus on spring style project test. include Spring Test and Spring Boot Test
  - [continuous-inspection-practice](https://github.com/xiaozhiliaoo/continuous-inspection-practice) Focus on **continous inspection** phase of continuous integration. sonar in action,code static analysis, p3c,sonar lint practice,findBugs.bug patterns. improve code,design quality

## distributed-system-infrastructure-engineering
- Observability
  - [tracing-practice](https://github.com/xiaozhiliaoo/tracing-practice) distributed tracing dapper,sleuth
  - [logging-practice](https://github.com/xiaozhiliaoo/logging-practice)  common logging with inotify, chukwa, FileBeat, fluentd, syslog , logstash, alibaba sls.
  - [monitoring-pracitce](https://github.com/xiaozhiliaoo/monitoring-practice.git) prometheus, springboot-admin
- [distributed-transaction-practice](https://github.com/xiaozhiliaoo/distributed-transaction-practice.git) seata, mq trancaction..


## Research
- [blockchain-practice](https://github.com/xiaozhiliaoo/blockchain-practice) blockchain learning
- [research-notes](https://github.com/xiaozhiliaoo/research-notes.git) explore interesting things


## Spring
- [interface21](https://github.com/xiaozhiliaoo/interface21): interface21 <font color=green>**`recommend`**</font>
- [ioc-practice](https://github.com/xiaozhiliaoo/ioc-practice): ioc include:picocontainer,guice,spring ioc...

## interview
- [interviews](https://github.com/xiaozhiliaoo/interviews) : interview prepare,leet&lint code,system design,work experience,project experience <font color=green>**`private`**</font>
- [KnowledgeSystem](https://github.com/xiaozhiliaoo/KnowledgeSystem) KnowledgeSystem Build
- [my-resume](https://github.com/xiaozhiliaoo/my-resume) my resume **`empty`**
    
    ##### System Design
    - [news_feed](https://github.com/xiaozhiliaoo/news_feed) news feed system **`prepare`**

## sourceCode-reading
- [Java Lang Package](https://github.com/xiaozhiliaoo/java-lang-reading): Java Lang Package design and implementation  **`empty`**
- [Java Collection Framework](https://github.com/xiaozhiliaoo/jcf-reading): Java Collection Framework  design and implementation **`empty`**
- [Java Util Concurrency](https://github.com/xiaozhiliaoo/juc-reading): Java Util Concurrency design and implementation **`empty`**
- [Java BIO/NIO/AIO](https://github.com/xiaozhiliaoo/io-reading): Java Lang IO,NIO design and implementation **`empty`**
- [Java Lambda&Stream](https://github.com/xiaozhiliaoo/java-function-stream-reading): java.util.function & java.util.stream package **`empty`**
- [Guava Collection Framework](https://github.com/xiaozhiliaoo/guava-collections-reading) Guava Collection Framework design and implementation **`empty`**
- [Guava Util Concurrency](https://github.com/xiaozhiliaoo/guava-concurrency-reading) Guava Util Concurrency design and implementation **`empty`**
- [Spring Framework](https://github.com/xiaozhiliaoo/spring-reading) Spring source code reading  **`empty`**
- [SpringMVC Framework](https://github.com/xiaozhiliaoo/spring-mvc-reading) SpringMVC source code reading **`empty`**
- [Mybatis](https://github.com/xiaozhiliaoo/mybatis-reading) Mybatis source code reading **`empty`**
- [Tomcat](https://github.com/xiaozhiliaoo/tomcat-reading) Tomcat source code reading **`empty`**



## computer-science
Focus on classic computers science course.

- [distributed-practice](https://github.com/xiaozhiliaoo/distributed-practice): distributed system       
- [database-system-practice](https://github.com/xiaozhiliaoo/database-system-practice) database-system-practice
- [operating-system-practice](https://github.com/xiaozhiliaoo/operating-system-practice) operating-system-practice
- [compliers-practice](https://github.com/xiaozhiliaoo/compliers-practice) compliers-practice
- [programming-language](https://github.com/xiaozhiliaoo/programming-language) PL learning
- [algorithm-practice](https://github.com/xiaozhiliaoo/algorithm-practice): data structure and algorithm,Algorithms by Robert Sedgewick,not leetcode
- [computer-system-practice](https://github.com/xiaozhiliaoo/computer-system-practice) computer architecture practice
- [network-practice](https://github.com/xiaozhiliaoo/network-practice) network practice

## notes
- [geektime-notes](https://github.com/xiaozhiliaoo/geektime-notes): geektime-notes
- [reading-notes](https://github.com/xiaozhiliaoo/reading-notes): reading-notes
- [meetup](https://github.com/xiaozhiliaoo/meetup.git): meetings I participated in.
