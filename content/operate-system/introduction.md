---
title: "Introduction"
date: 2021-04-13T21:29:50+08:00
draft: false
---

### 操作系统的主要功能

1. 从资源管理器的观点来看，操作系统的任务是高效地管理整个系统的各个部分；
2. 从扩展机的观点来看，其任务是为用户提供一台比物理计算机更易于使用的虚拟计算机；

### 系统调用

与进程有关，与文件系统有关

1. 与进程的创建和终止有关
2. 处理信号
3. 针对文件读写
4. 进行目录管理
5. 对信息进行保护
6. 用于时间管理

### 操作系统结构

1. 整体结构

   整个操作系统是一组函数的集合，其中每个函数在需要的时候可以去调用任何其他的函数

2. 分层结构

   把整个操作系统组织成一个层次结构，每一层软件都是在它的下层软件的基础上构造起来的

3. 虚拟机

4. 外核

   外核程序管理资源分配

5. 客户-服务器模型

   消息请求回复

### 操作系统

1. 进程管理
2. I/O设备管理
3. 存储管理
4. 文件管理



### 进程

1. 通信

2. 调度

   时钟中断 非抢占式调度算法 抢占式调度算法

   1. 所有系统

      公平 策略强制执行 平衡

   2. 批处理系统

      吞吐量 周转时间 CPU利用率

      1. 非抢占式调度算法
         1. 先到先服务
         2. 最短作业优先
      2. 抢占式调度算法
         1. 最短剩余时间优先
      3. 三级调度
         1. 准入调度器
         2. 内存调度器
         3. CPU调度器

   3. 交互式系统

      响应时间 均衡性

      两级调度： 内存调度 CPU调度

      1. 时间片轮转调度
      2. 优先级调度
      3. 多重队列
      4. 最短进程优先
      5. 保证调度算法
      6. 彩票调度算法
      7. 公平分享调度

   4. 实时系统

      满足截至时间 可预测性

      系统： 硬实时 软实时

      时间： 周期性 非周期性

   5. 策略与机制

   6. 线程调度







































