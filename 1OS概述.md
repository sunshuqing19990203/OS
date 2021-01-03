2021.1.3 孙书情 

[bilibili 清华大学陈渝向勇老师操作系统课程](https://www.bilibili.com/video/BV1js411b7vg)

[MOOC 华中科技大苏曙光操作系统原理](https://www.icourse163.org/learn/HUST-1003405007?tid=1450237469#/learn/content?type=detail&id=1214423432&sm=1)

# OS概述

**OS与应用软件最大的不同就是，OS对整个计算机具有控制权，具有很多特权指令，是可信任的一方。**

1. 主要内容：基本概念，操作系统的任务，中断及系统调用，内存管理，进程及线程，调度，同步，文件系统，I/O子系统

   操作系统是一个大型系统程序：**提供用户接口**，方便用户控制计算机；负责为应用程序**分配和调度软硬件资源，并控制与协调应用程序并发活动，帮助用户存取和保护信息。**

## 1.1OS 功能：

1. 进程管理（CPU管理）
2. 内存管理
3. 设备管理
4. 文件管理

## 1.2 OS 历史

1. 手工操作（无OS时代）（电子管时代）

2. 单道批处理系统（批量，单道串行，外设与CPU交替空闲忙碌）（晶体管时代）

3. 多道批处理系统（多道程序，宏观并行，当一个程序外设工作时，将另一个程序在CPU上运行，让CPU和外设尽量同时忙碌）

4. **分时技术与分时操作**：

   （中断技术，通道技术[专门处理外设与内存之间数据传输的处理机]）

   - 分时技术：主机以很短的 **时间片为单位**，把CPU分配给每个终端使用，直到所有作业被运行完
   - 分时系统的特点：多路调制性，独占性，**交互性**（及时响应用户的请求）
   - **UNIX **是第一个实用化的分时操作系统，主要用在服务器上面。

## 1.3 典型的操作系统

**BIOS基本输入输出程序**

嵌入式操作系统约等于实时操作系统，典型的**嵌入式操作系统**有Andriod









各章节知识点总结，欢迎自取～～
【操作系统】 Operation System 第一章：概述
https://blog.csdn.net/iwanderu/article/details/103934127
【操作系统】 Operation System 第二章：操作系统基础操作
https://blog.csdn.net/iwanderu/article/details/103934399
【操作系统】 Operation System 第三章：连续式内存分配
https://blog.csdn.net/iwanderu/article/details/103934647
【操作系统】 Operation System 第四章：非连续式内存分配
https://blog.csdn.net/iwanderu/article/details/103946219
【操作系统】 Operation System 第五章：虚拟内存
https://blog.csdn.net/iwanderu/article/details/103946338
【操作系统】 Operation System 第六章：页面置换算法
https://blog.csdn.net/iwanderu/article/details/103946369
【操作系统】 Operation System 第七章：进程和线程
https://blog.csdn.net/iwanderu/article/details/103946398
【操作系统】 Operation System 第八章：CPU调度
https://blog.csdn.net/iwanderu/article/details/103907536
【操作系统】 Operation System 第九章：同步
https://blog.csdn.net/iwanderu/article/details/103946424
【操作系统】 Operation System 第十章：信号量和管程
https://blog.csdn.net/iwanderu/article/details/103894660