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
  ### Spring Cloud Hystrix
    熔断器，容错管理的工具，通过熔断机制控制服务，对于延迟和故障提供更强大的 ***容错能力***。

  ### Spring Cloud Config
    配置中心，支持集中化管理集群配置，方便***统一管理***。
### 借鉴

  > [大话Spring Boot](http://www.ityouknow.com/springcloud/2017/05/01/simple-springcloud.html)

  > [Spring Cloud对比Dubbo](http://dockone.io/article/2408)

  > [Spring Cloud  与 Docker 实战](https://eacdy.gitbooks.io/-spring-cloud-docker/content/2%20Spring%20Cloud%20基础组件/2%20Spring%20Cloud基础组件.html)

  >[官方文档](http://projects.spring.io/spring-cloud/spring-cloud.html)
