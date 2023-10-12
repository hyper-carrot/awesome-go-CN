
**本列表旨在聚合和推广华人创作的优秀 Go 语言项目。欢迎也希望大家积极提交 PR。让我们共同打造它！**

🔑 Go 项目入列标准：

🔐 基本标准：

+ 需要是库项目或可运行的项目。不过 Go 语言相关的各种资源也是可以的。
+ 有一定的口碑。在提交入列申请时，项目的 Star 数原则上需要超过 50，最低 20 起步。
+ 最近仍然活跃。在提交入列申请时，项目的最后更新日期原则上需要在 3 个月之内，最久也要在半年以内。

🔏 加分项：

+ 适应范围越广越好。通用的框架、工具或中间件是最受欢迎的。
+ 上手越容易越好。代码规整、测试完备、文档清晰的项目最易上手。

_以上标准均不是绝对条件。我们会进行权衡，并尽量提升本列表的质量。_

**由于目录的跳转问题，目录和标题都需要使用英文。本文件中的项目介绍需要使用中文。**

### 目录（Contents）

- [Awesome Go](#awesome-go-China)
    - [Audio & Music](#audiomusic)
    - [Authentication & OAuth](#authentication--oauth)
    - [Command Line](#command-line)
    - [Configuration](#configuration)
    - [Continuous Integration](#continuous-integration)
    - [CSS Preprocessors](#css-preprocessors)
    - [Data Structures](#data-structures)
    - [Database](#database)
    - [Database Drivers](#database-drivers)
    - [DataSource](#datasource)
    - [Date & Time](#date--time)
    - [Distributed Systems](#distributed-systems)
    - [Email](#email)
    - [Embeddable Scripting Languages](#embeddable-scripting-languages)
    - [Financial](#financial)
    - [Forms](#forms)
    - [Game Development](#game-development)
    - [Generation & Generics](#generation--generics)
    - [Goroutines](#goroutines)
    - [GUI](#gui)
    - [Hardware](#hardware)
    - [Images](#images)
    - [Logging](#logging)
    - [Machine Learning](#machine-learning)
    - [Messaging](#messaging)
    - [Backstage Management System](#management-background)
    - [Miscellaneous](#miscellaneous)
    - [Natural Language Processing](#natural-language-processing)
    - [Networking](#networking)
    - [OpenGL](#opengl)
    - [ORM](#orm)
    - [Package Management](#package-management)
    - [Pool](#pool)
    - [Resource Embedding](#resource-embedding)
    - [Science and Data Analysis](#science-and-data-analysis)
    - [Security](#security)
    - [Serialization](#serialization)
    - [Storage](#storage)
    - [Template Engines](#template-engines)
    - [Testing](#testing)
    - [Text Processing](#text-processing)
    - [Third-party APIs](#third-party-apis)
    - [Utilities](#utilities)
    - [Validation](#validation)
    - [Version Control](#version-control)
    - [Video](#video)
    - [Web Frameworks](#web-frameworks)
        - [Middlewares](#middlewares)
            - [Actual middlewares](#actual-middlewares)
            - [Libraries for creating HTTP middlewares](#libraries-for-creating-http-middlewares)
        - [Routers](#routers)
    - [Windows](#windows)

- [Tools](#tools)
    - [Code Analysis](#code-analysis)
    - [Redis Analysis](#redis-analysis)
    - [Editor Plugins](#editor-plugins)
    - [Software Packages](#software-packages)
        - [DevOps Tools](#devops-tools)
        - [Other Software](#other-software)

- [Server Applications](#server-applications)

- [Resources](#resources)
    - [Benchmarks](#benchmarks)
    - [Conferences](#conferences)
    - [E-Books](#e-books)
    - [Twitter](#twitter)
    - [Websites](#websites)
        - [Tutorials](#tutorials)


## Audio/Music

*Libraries for manipulating audio.*


## Authentication & OAuth

*Libraries for implementing authentications schemes.*


## Command Line


### Standard CLI

*Libraries for building standard or basic Command Line applications*

- [readline](https://github.com/chzyer/readline)：纯Go实现的GNU Readline的CLI库，提供类似zsh的交互体验。

### Advanced Console UIs

*Libraries for building Console Applications and Console User Interfaces*

- [gcli](https://github.com/gookit/gcli) Go的命令行应用，工具库，运行CLI命令，支持命令行色彩、用户交互、进度显示、数据格式化显示、生成bash/zsh命令补全脚本

## Configuration

*配置文件解析库*

- [go-ini](https://github.com/go-ini/ini)：全能 INI 解析生成库
- [ini](https://github.com/gookit/ini): INI配置读取管理，支持多文件加载，数据覆盖合并, 解析ENV变量, 支持变量引用

## Continuous Integration

*Tools for help with continuous integration*

- [Cyclone](https://github.com/caicloud/cyclone)：一个打造容器工作流的持续集成和持续发布系统，使用 Go 语言实现，有详尽的中文文档，由 [@caicloud](https://github.com/caicloud) 实现。

## CSS Preprocessors

*Libraries for preprocessing CSS files*


## Data Structures

*通用的数据结构和算法库。*

- [go-tagexpr](https://github.com/bytedance/go-tagexpr)：一个可用于字段验证等目的Go结构体标记表达式库。


## Database

*用Go语言实现的数据库。*

- [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL)：利用区块链技术的一个众包SQL数据库。
- [DTM](https://github.com/yedf/dtm)：解决分布式事务的中间件。框架层代为处理幂等、空补偿等问题，且适用于多语言技术栈。
- [Godis](https://github.com/hdt3213/godis)：一个用 Golang 实现的 Redis 服务器，支持 Redis 的大多数功能并自带集群模式
- [LedisDB](http://ledisdb.com)：一个高性能的分布式数据库，类似于并兼容Redis。
- [Tedis](https://github.com/eleme/tedis)：Tedis 是一个基于[TiKV](https://github.com/tikv/tikv)的NoSQL数据库，拥有强一致性，并且兼容 Redis 协议。
- [TiDB](https://github.com/pingcap/tidb)：一个支持SQL的分布式数据库，其参考了Google F1的设计，兼具NoSQL和传统关系型数据库的优点。
- [NutsDB](https://github.com/xujiajun/nutsdb): 一个简单、高性能、内嵌型的KV数据库，支持事务以及多种数据结构包括list, set, sorted set。
- [rosedb](https://github.com/roseduan/rosedb)：一个仿 Redis 的内嵌 k-v 数据库，支持 string、list、hash、set、sorted set 多种数据结构。

*Database tools.*


*SQL query builder, libraries for building and using SQL.*



## Database Drivers

*Libraries for connecting and operating databases.*

* Relational Databases

* NoSQL Databases

* Search and Analytic Databases

## DataSource

*Libraries or tools for Data source binding, or data migration.*

## Date & Time

*Libraries for working with dates and times.*



## Distributed Systems

*用于构建分布式系统的库/框架，或可运行的分布式系统。*

- [eru](https://github.com/projecteru2/core)：一款可以混合调度编排 container/vm 的平台组件。
- [glow](https://github.com/chrislusf/glow)：一个易于使用的分布式系统，可作为Hadoop、Spark、Flint、Samza的替代品。
- [hprose-golang](https://github.com/hprose/hprose-golang)：一个支持 20 多种语言的功能强大，简单易用的高性能动态 RPC，该版本是它的 go 语言实现。
- [kafka-pusher(taiji)](https://github.com/crask/kafka-pusher)：Kafka-pusher(又名太极)是kafka服务的消费者实现，它可以拉取(pull)消费kafka中的消息，并通过HTTP方式推送(push)给任何接口。
- [mqproxy](https://github.com/crask/mqproxy)：mqproxy是kafka的http代理服务。
- [GoFrame](https://github.com/gogf/gf)：一款模块化、高性能、企业级的Go基础开发框架，并实现了比较完善的基础设施建设以及开发工具链。
- [Kratos](https://github.com/go-kratos/kratos) 轻量级、可定制、拥抱云原生和开源标准的 Go 微服务框架，帮助您快速实现可支撑大型互联网业务的微服务应用。

## Email

*Libraries that implement email creation and sending*




## Embeddable Scripting Languages

*Embedding other languages inside your go code*



## Financial

*Packages for accounting and finance*



## Forms

*Libraries for working with forms.*



## Game Development

*游戏开发库。*

- [Leaf](https://github.com/name5566/leaf)：一个高效的游戏服务器开发框架，适用于各类游戏服务器的开发。
- [mqant](https://github.com/liangdas/mqant)：高性能分布式游戏服务器开发框架，可用于游戏后端服务器以及物联网后端服务器开发。


## Generation & Generics

*Tools to enhance the language with features like generics via code generation*



## Goroutines

*管理和调度 goroutines 的工具库*

- [ants](https://github.com/panjf2000/ants): A high-performance goroutine pool in Go.


## GUI

*Libraries for building GUI Applications*



## Hardware

*Libraries, tools, and tutorials for interacting with hardware.*


## Images

*Libraries for manipulating images.*


## Logging

*Libraries for generating and working with log files.*


## Machine Learning

*与机器学习有关的库。*

- [gorse](https://github.com/zhenghaoz/gorse)：一个高性能的、基于协同过滤的推荐系统代码包。


## Messaging

*用于实现消息系统的库，或可运行的消息系统。*

- [goim](https://github.com/Terry-Mao/goim)：一个轻量级、高性能的即时通讯服务器。
- [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster)：一个易集群化的的Comet服务器，支持Web Socket和TCP协议。
- [KiteQ](https://github.com/blackbeans/kiteq)：支持多种持久化方案的消息队列框架。

## Backstage Management System

*管理后台相关的项目。*

- [go-ldap-admin](https://github.com/eryajf/go-ldap-admin)：🌉 基于Go+Vue实现的openLDAP后台管理项目。

## Miscellaneous

*These libraries were placed here because none of the other categories seemed to fit*


## Natural Language Processing

*Libraries for working with human languages.*


## Networking

*可在网络中任意一层工作的库。*

- [gnet](https://github.com/panjf2000/gnet): A high-performance, lightweight, nonblocking, event-loop networking library written in pure Go.
- [Kube-OVN](https://github.com/alauda/kube-ovn): 基于 OVN 的 Kubernetes 网络编排系统。
- [link](https://github.com/funny/link)：灵活的网络层脚手架，可用来快速搭建各种项目所需的网络层。
- [Pholcus](https://github.com/henrylee2cn/pholcus)：Pholcus（幽灵蛛）是一款纯Go语言编写的支持分布式的高并发、重量级爬虫软件，定位于互联网数据采集，为具备一定Go或JS编程基础的人提供一个只需关注规则定制的功能强大的爬虫工具。
- [Surfer](https://github.com/henrylee2cn/surfer)：Surfer 是一款Go语言编写的高并发 web 客户端，拥有surf与phantom两种下载内核，高度模拟浏览器行为，可实现模拟登录等功能。
- [Tao](https://github.com/leesper/tao)：轻量级TCP异步框架。
- [Teleport](https://github.com/henrylee2cn/teleport)：Teleport是一个通用、高效、灵活的TCP Socket框架。可用于Peer-Peer对等通信、RPC、长连接网关、微服务、推送服务，游戏服务等领域。


## OpenGL

*Libraries for using OpenGL in Go.*



## ORM

*实现对象-关系映射或其它数据映射技术的库。*

- [GORM](https://github.com/jinzhu/gorm): 程序员友好的全功能ORM，API 简洁，支持Model之间一对一、一对多、多对多关联，还可通过插件扩展功能等。
- [xorm](https://github.com/go-xorm/xorm)：一个简单且强大的ORM库，支持MySQL、Postgres、TiDB、SQLite 3、MSSQL、Oracle等。

## Package Management

*实现代码包或/和依赖管理的库。*

- [gopm](http://gopm.io)：一个代码包和依赖管理工具。它无需Git、Hg等版本管理工具，就可以下载指定版本的Go代码包。

## Pool

*具有通用功能的对象池。*

- [go-commons-pool](https://github.com/jolestar/go-commons-pool)：通用的Golang对象池，改写自Java版本的 [Apache Commons Pool](https://commons.apache.org/proper/commons-pool/)，具有丰富的配置选项以及超时机制。
- [slab](https://github.com/funny/slab)：基于slab算法的内存池，提供无锁内存池和基于`sync.Pool`的内存池两种实现。

## Resource Embedding



## Science and Data Analysis

*Libraries for scientific computing and data analyzing.*


## Security

*用于安全防护的库、框架或服务器。*

- [gocaptcha](https://github.com/hanguofeng/gocaptcha)：goCaptcha是支持中文和干扰线的验证码服务器。


## Serialization

*Libraries and tools for binary serialization*

- [fastbin](https://github.com/funny/fastbin)：一个零配置的通讯协议代码生成工具，从Go结构体反向生成通讯协议代码，适用于各类游戏服务端开发。
- [hprose](https://github.com/hprose/hprose-golang)：一个支持 20 多种语言的序列化库，该版本是它的 go 语言实现。

## Storage

*存储相关的软件库以及系统。*

- [gotgt](https://github.com/gostor/gotgt)：一个完整的用户态实现的iSCSI target，后端可以适配任何其他存储系统。

## Server Applications

*通用的独立服务器软件。*

- [Ran](https://github.com/m3ng9i/ran)：一款支持 Digest 认证、gzip 压缩、TLS 加密等功能的静态 web 服务器。


## Template Engines

*Libraries and tools for templating and lexing.*



## Testing

*Libraries for testing codebases and generating test data.*

* Testing Frameworks

* Mock

* Fuzzing and delta-debugging/reducing/shrinking

## Text Processing

*Libraries for parsing and manipulating texts.*

* Specific Formats


## Text Search

*全文搜索引擎或服务器。*

- [wukong](https://github.com/huichen/wukong)：高效、高可定制的全文搜索引擎。

## Third-party APIs

*提供针对第三方平台的访问和操作功能的库。*

- [wechat](https://github.com/chanxuehong/wechat)：提供针对微信公众平台、微信企业号、微信商户平台和微信支付的相关功能的Go语言库。
- [GoPay](https://github.com/iGoogle-ink/gopay)：微信支付、支付宝支付等的Go版本SDK。

## Utilities

*有用的工具。*

- [bat](https://github.com/astaxie/bat)：bat是类似curl的对人类友好的命令行程序，可以用来调试HTTP服务。
- [bcbc](https://github.com/hexindai/bcbc)：根据银联银行卡号查询所在银行以及银行卡类型的工具。
- [g](https://github.com/voidint/g)：golang多版本管理器。
- [soar](https://github.com/XiaoMi/soar)：一个对SQL进行优化和改写的自动化工具。由小米人工智能与云平台的数据库团队开发与维护。
- [tsdump](https://github.com/voidint/tsdump)：数据库表结构导出工具。


## Validation

*Libraries for validation.*



## Version Control

*用于进行版本控制的库或服务器。*

- [Gitea](https://github.com/go-gitea/gitea)：一个开源社区驱动的轻量级代码托管解决方案，后端采用Go编写，采用MIT许可证。
- [Gogs](https://github.com/gogits/gogs)：一款可轻易搭建的自助Git服务。

## Video

*Libraries for manipulating video.*

- [lal](https://github.com/q191201771/lal)：Golang 直播流媒体网络传输服务

## Web Frameworks

*Web开发框架。*

- [Beego](http://beego.me)：Beego是一个快速开发 Go 应用的 HTTP 框架，他可以用来快速开发 API、Web 及后端服务等各种应用，框架具有简单化、智能化、模块化、高性能等特性。
- [Faygo](https://github.com/henrylee2cn/faygo)：Faygo 是一款快速、简洁的Go Web框架，可用极少的代码开发出高性能的Web应用程序（尤其是API接口）。只需定义 struct Handler，Faygo 就能自动绑定、验证请求参数并生成在线API文档。
- [Gin-X](https://github.com/hhxsv5/gin-x) 基于[Gin](https://github.com/gin-gonic/gin)封装的开发模板，以便快速上手。
- [Macaron](http://go-macaron.com)：高生产力和模块化设计的 Go Web 框架。
- [snake](https://github.com/1024casts/snake) 一款小巧的基于Go构建的开发框架，可以快速构建API服务或者Web网站进行业务开发，遵循SOLID设计原则

### Middlewares

#### Actual middlewares

- [Gin Metrics](https://github.com/kylesliu/gin_metrics)：基于Gin的一个中间件，负责将请求的日志以*Metrics*个方式暴露出来，通过Prometheus抓取之后在Grafana展示。只要不到10分钟即可在原有的架构基础上搭建一套监控系统。
- [Gaea](https://github.com/XiaoMi/Gaea)：小米中国区电商研发部研发的基于MySQL协议的数据库中间件。
- [Overlord](https://github.com/bilibili/overlord)：针对Memcache和Redis的代理及集群管理中间件，致力于提供自动化高可用的缓存服务解决方案。

#### Libraries for creating HTTP middlewares

### Routers

*Web请求路由器。*

- [Gorouter](https://github.com/xujiajun/gorouter): Gorouter是一个简单高性能的http router，支持正则，基于Gorouter很方便组建自己的web框架以及编写RestFul Api。


# Tools

Go software and plugins.


## Code Analysis

* [go-checkstyle](https://github.com/qiniu/checkstyle) 根据go语言规范，参考 java
checkstyle 实现的代码风格检查工具

## Redis Analysis

* [go-redis-memory-analysis](https://github.com/hhxsv5/go-redis-memory-analysis) 🔎 根据Key前缀分析Redis内存占用情况，并将分析结果导出为CSV文件。


## Editor Plugins


## Software Packages

Software written in Go.


### DevOps Tools

* [http-log-exporter](https://github.com/songjiayang/http-log-exporter) 一个将 Nginx、Gin 等 HTTP 请求日志转化为 Prometheus Metrics 的工具，支持 histogram 和 exemplar 配置。

### Other Software







# Resources

Where to discover new Go libraries.


## Benchmarks



## Conferences

- [GopherChina](http://gopherchina.org)：Go语言官方认可的中国用户社区会议。


## E-Books

- [Go命令教程](https://github.com/hyper-carrot/go_command_tutorial)：讲述Go语言标准工具的使用方法，展现Go语言给力的工程理念。
- [Go名库讲解](https://github.com/Unknwon/go-rock-libraries-showcases)：一套针对Go语言的第三方库进行评测讲解的集博客、示例与语音视频为一体的综合教程。
- [Go Web编程](https://github.com/astaxie/build-web-application-with-golang)：讲述使用Go语言进行Web编程的方方面面。
- [Go学习笔记](https://github.com/qyuhen/book)：雨痕的个人学习笔记。
- [42分钟乱入 GAE(with go1)](http://chaos2.zoomquiet.top/go1/build/html/) 大妈的实例功能开发自学笔记


## Online Tutorials

- [Go语言第一课](http://www.imooc.com/view/345)：Go语言入门的必备知识扩散。【免费】
- [Go 编程基础](https://github.com/Unknwon/go-fundamental-programming)：新手入门必备教程。【免费】
- [Go 核心技术36讲](https://time.geekbang.org/column/intro/112)：深入讲解Go语言核心技术的在线课程。【付费】


## Websites

- [GoHackers](https://gohackers.bearychat.com)：GoHackers技术社群，基地在北京，以在线即时交流为主，同时会不定期主办或参与相关的技术活动和技术会议。此社群同时拥有一系列微信群、微信公众号`GoHackersZero`，GitHub组织[`GoHackers`](https://github.com/GoHackers)，以及知识星球[`GoHackers VIP`](https://wx.zsxq.com/dweb2/index/group/458122885418)。
- [Go中国技术社区](https://gocn.vip)
- [Go语言中文网](http://studygolang.com)
- [Golang中国](http://www.golangtc.com)
- [Go Walker](https://gowalker.org)


## Windows



### Tutorials

