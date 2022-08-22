# JDBC

## JDBC的三层架构

### DAO层(数据访问层)

​	**DAO层**主要是对数据库的数据进行操作(增删改查)的一些类。

### Service层(业务层)

​	**Service层**主要是对DAO层的操作进行整合的一些类,也就是实现客户需求的业务逻辑

### view层(用户使用层)

​	**view层**是给用户看和使用的一个层,可以成为是UI层,主要完成用户交互接口和后台数据的连接。

*************

以上是JDBC的层级架构,以下是一些常用层的解释

### DBUtil(数据库连接层)

​	**DBUtil**主要是连接数据库和java程序的一个类

​	**DBHelper**是是用来开启和关闭数据库的一个类

### pojo包(普通类)

​	**pojo**包主要是放一些实体类的包,也可以称为放某些对象,比如人有年龄、姓名、性别等等属性,那么把人这个类形成一个对象后,就把这个类放到pojo包里面



## 一些方法和关键词的说明

### Connection

​	Connection是一个接口,在java.sql的jar包中



### Question

### 关于DBHelper的问题



#### 1.java.sql.driver是干嘛的

![](F:\program\blog\tscwit.github.io\docs\study\jdbc\assets/driver是干嘛用的.png)

A:加载db的驱动

#### 2.Connection是什么类,他有什么作用,他要怎么使用

![](F:\program\blog\tscwit.github.io\docs\study\jdbc\assets/Connection的Q.png)



#### 3.defalut关键词的作用

​	defalut似乎有两种用法,一种是修饰接口,一种是修饰类,接口的还不晓得,之后回来补。

​	当defalut修饰类的时候,表示这个类有默认的访问权限。

​	defalut(默认访问权限)修饰的类在本类和同包中能够互相访问。