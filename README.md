# 中小团队的架构师入门实践手册

本实践手册不求看似面面俱到，而是尽量做得在特定技术栈下立马上手就能搭建环境跑起来.

## 技术栈结构

* .NET
  * 框架
    * ABP
  * 构建与包管理
    * Nuget
    * dotnet cli
    * MSBuild
  * 测试
    * BDD: Specflow / Xunit.Gherkin.Quick
    * TDD: xUnit
  * 安全
    * Identity Server
* Java
  * 框架
    * Spring Boot
  * 构建与包管理
    * Maven
    * Gradle
  * 测试
    * BDD: Cucumber
  * 安全
* Python
  * 框架
    * Django
  * 测试
    * BDD: Behave  
* Node
  * 框架
    * Midway ( Egg.js )
    * Nest.js ( Express.js )
    * Nx (全栈)
* 前端
  * 框架
    * Angular
    * Next.js (React)
    * Nuxt.js (Vue)
  * 测试
    * TDD: Jest
  * 安全
    * 跨域访问
* DevOps
  * Web Server
    * Nginx ( +OpenResty )
    * IIS
    * [Gunicorn](https://gunicorn.org)
  * 容器化
    * Docker
* Message Queue
  * RabbitMQ  
* 数据库
  * Redis
  * PostgreSQL
  * MySQL
  * SQL Server
* 工程化
  * Webpack
  * 持续集成
    * Jenkins
    * Github Actions
* 最佳实践
  * [Python](pythonguidecn.readthedocs.io/zh/latest/index.html)
  * [Node.js](https://github.com/goldbergyoni/nodebestpractices/blob/master/README.chinese.md)
