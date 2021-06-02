### SpringBoot入门

从根本上来说，Spring Boot的项目只是普通的Spring项目，只是它们正好用到了Spring Boot的起步依赖和自动配置而已。

#### Spring开发一个Hello World Web应用需要做什么

1. 一个项目结构，其中包括一个必要依赖的Maven或Gradle构建文件
2. 一个web.xml文件，声明Spring的DispatcherServlet
3. 一个启用了Spring MVC 的Spring配置
4. 一个控制器类，以“Hello World”响应HTTP请求
5. 一个用于部署应用的Web应用服务器，比如Tomcat



#### SpringBoot最重要的四个核心

1. 自动配置

   针对很多Spring应用常见的应用功能，能自动提供相关配置

2. 起步依赖

   告诉SpringBoot需要什么就能引入需要的**库**

3. 命令行界面

   可选特性，借此你只需写代码就能完成完整的应用程序，
   无需传统项目构建。

4. Actuator

   提供在运行时检视应用程序内部情况的能力



