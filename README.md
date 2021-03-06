# TLS客户端认证的例子

本项目提供TLS客户端认证的例子，包括Client和Server。

## 准备工作

本项目已经在`certs`目录下准备好了Client和Server需要的证书、私钥、Keystore和Truststore。如果你想自己动手做一遍可以看[证书准备工作](certs)，你也可以跳过本步骤直接看下面的文章。

## 如何使用例子

启动本项目中的任意Server端，然后用任意Client端访问。如果用本例子提供的服务端启动脚本，则访问地址统一是`https://localhost:8443`。

## Client例子

* [Curl](client/curl)
* [Postman](client/postman)
* [HttpClient](client/httpclient)
* [OkHttp](client/okhttp)
* Netty
* [Reactor Netty](client/reactor-netty)
* [Spring Boot - RestTemplate](client/spring-boot)
* Spring Cloud Open Feign
* [Go net/http](client/go)

## Server例子

* [Nginx](server/nginx)
* [Haproxy](server/haproxy)
* [Tomcat](server/tomcat)
* [Jetty](server/jetty)
* Netty
* [Reactor Netty](server/reactor-netty)
* [Ingress Nginx](server/ingress-nginx)
* [Go net/http](server/go)

## 对TLS不了解？

* [如何在Tomcat中做TLS客户端认证](https://segmentfault.com/a/1190000018673904)
* [X.509、PKCS文件格式介绍](https://segmentfault.com/a/1190000019008423)，如果遇到证书格式问题请看这篇文章
