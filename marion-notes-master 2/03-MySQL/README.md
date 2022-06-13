# 【高性能MySQL（第3版）(博文视点出品)】

## 第1章 MySQL架构与历史

### 1.1 MySQL逻辑架构

### 1.2 并发控制

### 1.3 事务

### 1.4 多版本并发控制

### 1.5 MySQL的存储引擎

### 1.6 MySQL时间线（Timeline）

### 1.7 MySQL的开发模式

### 1.8 总结

## 第2章 MySQL基准测试

### 2.1 为什么需要基准测试

### 2.2 基准测试的策略

### 2.3 基准测试方法

### 2.4 基准测试工具

### 2.5 基准测试案例

### 2.6 总结

## 第3章 服务器性能剖析

### 3.1 性能优化简介

### 3.2 对应用程序进行性能剖析

### 3.3 剖析MySQL查询

### 3.4 诊断间歇性问题

### 3.5 其他剖析工具

### 3.6 总结

## 第4章 Schema与数据类型优化

### 4.1 选择优化的数据类型

### 4.2 MySQL schema设计中的陷阱

### 4.3 范式和反范式

### 4.4 缓存表和汇总表

### 4.5 加快ALTER TABLE操作的速度

### 4.6 总结

## 第5章 创建高性能的索引

### 5.1 索引基础

### 5.2 索引的优点

### 5.3 高性能的索引策略

### 5.4 索引案例学习

### 5.5 维护索引和表

### 5.6 总结

## 第6章 查询性能优化

### 6.1 为什么查询速度会慢

### 6.2 慢查询基础：优化数据访问

### 6.3 重构查询的方式

### 6.4 查询执行的基础

### 6.5 MySQL查询优化器的局限性

### 6.6 查询优化器的提示（hint）

### 6.7 优化特定类型的查询

### 6.8 案例学习

### 6.9 总结

## 第7章 MySQL高级特性

### 7.1 分区表

### 7.2 视图

### 7.3 外键约束

### 7.4 在MySQL内部存储代码

### 7.5 游标

### 7.6 绑定变量

### 7.7 用户自定义函数

### 7.8 插件

### 7.9 字符集和校对

### 7.10 全文索引

### 7.11 分布式（XA）事务

### 7.12 查询缓存

### 7.13 总结

## 第8章 优化服务器设置

### 8.1 MySQL配置的工作原理

### 8.2 什么不该做

### 8.3 创建MySQL配置文件

### 8.4 配置内存使用

### 8.5 配置MySQL的I/O行为

### 8.6 配置MySQL并发

### 8.7 基于工作负载的配置

### 8.8 完成基本配置

### 8.9 安全和稳定的设置

### 8.10 高级InnoDB设置

### 8.11 总结

## 第9章 操作系统和硬件优化

### 9.1 什么限制了MySQL的性能

### 9.2 如何为MySQL选择CPU

### 9.3 平衡内存和磁盘资源

### 9.4 固态存储

### 9.5 为备库选择硬件

### 9.6 RAID性能优化

### 9.7 SAN和NAS

### 9.8 使用多磁盘卷

### 9.9 网络配置

### 9.10 选择操作系统

### 9.11 选择文件系统

### 9.12 选择磁盘队列调度策略

### 9.13 线程

### 9.14 内存交换区

### 9.15 操作系统状态

### 9.16 总结

## 第10章 复制

### 10.1 复制概述

### 10.2 配置复制

### 10.3 复制的原理

### 10.4 复制拓扑

### 10.5 复制和容量规划

### 10.6 复制管理和维护

### 10.7 复制的问题和解决方案

### 10.8 复制有多快

### 10.9 MySQL复制的高级特性

### 10.10 其他复制技术

### 10.11 总结

## 第11章 可扩展的MySQL

### 11.1 什么是可扩展性

### 11.2 扩展MySQL

### 11.3 负载均衡

### 11.4 总结

## 第12章 高可用性

### 12.1 什么是高可用性

### 12.2 导致宕机的原因

### 12.3 如何实现高可用性

### 12.4 避免单点失效

### 12.5 故障转移和故障恢复

### 12.6 总结

## 第13章 云端的MySQL

### 13.1 云的优点、缺点和相关误解

### 13.2 MySQL在云端的经济价值

### 13.3 云中的MySQL的可扩展性和高可用性

### 13.4 四种基础资源

### 13.5 MySQL在云主机上的性能

### 13.6 MySQL数据库即服务（DBaaS）

### 13.7 总结

## 第14章 应用层优化

### 14.1 常见问题

### 14.2 Web服务器问题

### 14.3 缓存

### 14.4 拓展MySQL

### 14.5 MySQL的替代品

### 14.6 总结

## 第15章 备份与恢复

### 15.1 为什么要备份

### 15.2 定义恢复需求

### 15.3 设计MySQL备份方案

### 15.4 管理和备份二进制日志

### 15.5 备份数据

### 15.6 从备份中恢复

### 15.7 备份和恢复工具

### 15.8 备份脚本化

### 15.9 总结

## 第16章 MySQL用户工具

### 16.1 接口工具

### 16.2 命令行工具集

### 16.3 SQL实用集

### 16.4 监测工具

### 16.5 总结

*XMind - Trial Version*