# hrmapp
HR System: Spring + Mybatis实战

相关技术介绍
本系统主要涉及三个开源框架：MyBatis3, Spring 和表示层框架JQuery(之后将会替换为VueJS或者Angular)

1. 传统表示层技术 JSP
2. MVC框架
3. Spring框架
4. MyBatis

系统结构
本系统严格采用Java EE应用结构，主要有如下几个分层：
1. 表现层。由JSP页面组成（后续改为VUEJS或者Angular)
2. MVC层。使用Spring MVC技术。
3. 业务逻辑层： 主要由Spring IoC容器管理的业务逻辑组件组成。
4. DAO层。
5. 领域对象层
6. 数据库服务层。使用MySQL数据库存储持久化数据。

