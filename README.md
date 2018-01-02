# jsets-jdbc-spring-boot-starter

在开发实践中，遇到数据库表不多的项目，比如一些非业务性的功能系统、一些职责单一的微服务系统。如果集成MyBatis、Hibernate等框架，相对整个系统而言有些偏重，采用jdbctemplate来实现则更为轻量。针对一些大量批处理操作、LOB字段操作、存储过程操作、复杂SQL操作的情况使用jdbctemplate则更加直接和便捷。

**功能简介：**

1：支持常用的JPA注解，实体经过注解，进行增、删、改、getById、listAll不需要写SQL像Hibernate一样；查询时不需要写RowMapper会根据注解自动填充。

2：简化的批处理操作API。

4：简化的分页操作API。

5：灵活的链式查询API。

6：未经过JAP注解的实体，也能在查询时进行字段-属性的动态映射和值填充。

7：灵活强大的SQL构建工具SqlBuilder。
