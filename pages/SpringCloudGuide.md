#  SpringCloud
***
## 微服务架构支持

| SpringCloud     |               |
| -------------   |:-------------:|
| 服务注册中心      | Spring Cloud Eureka |
| 服务调用方式      | RESTful API         |  
| 服务网关         | Spring Cloud Zuul |       
|断路器            |Spring Cloud Hystrix |
|配置中心|Spring Cloud Config|
|服务跟踪|Spring Cloud Sleuth|
|消息总线|Spring Cloud Bus|
|数据流|Spring Cloud Stream|
|批量任务|Spring Cloud Task|

***
* ### Spring Cloud Eureka
    基于 [Netflix Eureka](https://github.com/Netflix/eureka) 进行了二次封装，由Eureka服务端和客户端组成，起到 ***服务发现*** 的作用
      服务端：服务注册中心

      客户端：服务提供者／服务消费者


### 借鉴
  > [Spring Cloud对比Dubbo](http://dockone.io/article/2408)

  > [Spring Cloud  与 Docker 实战](https://eacdy.gitbooks.io/-spring-cloud-docker/content/2%20Spring%20Cloud%20基础组件/2%20Spring%20Cloud基础组件.html)

  >[官方文档](http://projects.spring.io/spring-cloud/spring-cloud.html)
