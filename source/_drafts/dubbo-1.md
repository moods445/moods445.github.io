---
title: dubbo-1
tags:
categories: dubbo
---

#  概念

## RPC

rpc( Remote Procedure Call )是一个计算机通信协议

远程过程调用和本地方法调用是一个相对的概念。

对比：

1. 本地方法调用是调用本地方法
2. 远程过程调用。调用远程方法，通常是通过网络，所有就有两种调用方式
   1. 通过 http
   2. 通过 tcp

一般包括三种定义：

1. 调用的是哪个类或接口
2. 调用的是哪个方法
3. 入参



# dubbo

Java rpc 框架，现在官网称为 Java 服务框架

# 架构

![dubbo架构](https://dubbo.apache.org/imgs/user/dubbo-architecture.jpg)

1. Provider。服务提供方
2. Consumer。服务消费方
3. Registry。注册中心
4. Monitor。监控中心
5. Container。运行容器

