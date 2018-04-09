# java学习计划
## java SE基础 [教程参考](http://www.runoob.com/java/java-basic-syntax.html)
### java语法基础 
* java基础数据类型，
	* 值类型：int，boolean，long，byte，double,float char 等
	* 引用类型  Object, String, 数组等
* java运算符操作
	* 数值操作符，加减乘除，位运算等
	* 逻辑操作符，与或非，异或等

* 分支控制
	* if-else
	* switch-case

* 循环控制
	* for循环 三要素
	* while循环 
	* continue，break等关键字使用

* 写一些功能控制，打印9＊9乘法表格等等

* 递归控制
	* 斐波那契数列求和
	* 求最大公约数，辗转相除法
	* 汉诺塔

* 编程思想
	* 理解程序里的时空转换。 空间对应内存占用，时间对应运行时间

* debug 技能训练，多写多调试多积累

### java面向对象 
* 类定义，属性方法的定义
* 类的作用域private，public，protected，default等
* 接口，抽象类，类等概念
* 类之间的关系，继承和组合
* java构造函数
* java变量初始化过程 
* 重写和重载的区别
* 多态的实现
* 面向对象编程的核心原则，高内聚低耦合

* 定义一个计算面积的接口，分别定义，矩形，圆形，三角形实现该接口并计算面积

### 数据结构和算法
* 理解线性表 List，Array的数据结构
* 理解散列表 设计散列函数
* 树和图的理解
	* 树的遍历方式 前序，中序，后序
	* 图的遍历方式 深度优先dfs和宽度优先bfs

* 排序算法 分析时间和空间复杂度 [排序算法资料](https://www.cnblogs.com/onepixel/articles/7674659.html) 
	* 冒泡，选择，插入，希尔排序等
	* 快速排序，堆排序，归并排序等
	* 计数排序，基数排序等

### 高级教程
* java 集合框架学习List,Set,Map等接口与实现
	* HashMap实现原理
	* 集合类api使用和理解
	
* java Exception 类继承体系学习，不同异常的区别
	* Throwable 
	* Exception  RuntimeException
	* Error

* java IO流设计模式学习 
	* 装饰模式
	* 字节流和字符流
	* 读写文件

* java 多线程并发相关
	* Thread 和Runnable的关系
	* 线程池的选型和使用
	* 并发编程，锁信号量，线程安全，ThreadLocal等概念

## 开发工具使用
### maven <a href ="https://maven.apache.org/guides/getting-started/index.html">maven入门介绍</a>   或者 gradle的使用<a href ="https://gradle.org/guides/#getting-started">gradle入门介绍</a>
* maven三坐标 groupId，artifactId，version
* maven dependency管理，直接使用dependencies和dependencyManagement的区别与优缺点
* maven 构建生命周期，clean validate compile test package verify install site deploy, 了解其中关键几个构建过程
* maven 插件使用
* maven 其他功能点，参考官方文档说明
* 创建一个maven工程进行打包

### eclipse 和 idea的使用
### git 和svn 使用

## java EE
### java web工程组成结构

### tomcat web容器学习

### java servlet 和jsp相关学习

### 学一些html，css，js等技术，然后可以做一些有意思的东西

### 搭建一个简单的web项目并在tomcat容器中运行

## 数据库技术学习
### 数据库操作sql语句使用主要
* 数据定义语言（DDL）、数据操作语言（DML）、数据控制语言（DCL）和事物控制语言（TCL）。
* jdbc or jndi技术连接mysql或者oracle数据库
* 数据库连接池的原理和使用，c3p0,dbcp,dbcp2,druid等开源连接池的使用

## web框架学习
### Spring，SpringMVC，mybatis的学习与使用
### 测试框架学习，junit 和Mock的学习
### 一些流行库的学习，例如http库和json，xml解析库的学习和使用,jedis的使用


## 分布式相关技术学习
### 缓存技术 redis memcache
### 分布式服务框架  rpc相关框架
### zookeeper 和 etcd
### 分布式消息中间件kafka
### 搜索引擎elasticsearch
### 分布式文件系统了解hdfs，分布式计算框架MapReduce学习，hadoop集群，spark集群，storm集群了解
### noSql技术了解，学习hbase，mangodb
