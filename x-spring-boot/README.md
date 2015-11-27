
#x-spring-boot
这是按照 spring boot 的官方入门指南写的包含有

    * rest 服务

    * 带视图的web应用

    * 构建war包部署

#如何运行:

    直接运行 hello.Application  的 main 方法

#如何打包:

    maven clean package

#部署到tomcat的注意事项:

hello.Application 必须要继承 SpringBootServletInitializer 类
