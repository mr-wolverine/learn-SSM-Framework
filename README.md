# Java高并发秒杀总结
## 一、数据层技术回顾
### 1. 数据库设计和实现
1. 表结构、列和索引；
2. 熟练掌握DDL（数据库定义语言）的写法

### 2. MyBatis理解和使用技巧
1. MyBatis建议使用DAO接口+XML的方法，即DAO接口中的每一个方法对应XML中的一条SQL；
2. Service调用这些接口实现业务逻辑。

### 3. MyBatis和Spring的高效使用
配置自动的包扫描，扫描XML文件；

## 二、业务层的技术回顾
### 1. 业务接口设计和封装
站在使用者的角度去设计接口，而不是想着如何去实现；

### 2. Spring IOC配置技巧
1. 第三方类库、一次性配置（如声明式事务）使用XML配置；
2. 对于自己开发的DAO，Service，Controler使用注解；

### 3. Spring声明式事务

## 三、WEB层技术回顾
### 1. Restful接口应用

### 2. SpringMVC使用技巧

### 3. 前端交互分析

### 4. Bootstrap和JS使用


## 四、并发优化
### 1. 系统瓶颈点分析

### 2. 事务，锁，网络延迟理解

### 3. 前端、CDN、缓存等理解使用

### 4. 集群化部署