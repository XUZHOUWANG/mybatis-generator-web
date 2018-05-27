## mybatis代码生成器web版

### 1. 概述

目前springboot + mybatis的框架非常流行。但是，我们在实际编程中，经常会碰到
手写的mybatis mapper xml文件。这是非常消耗体力的。mybatis官方提供mybatis-generator
的解决方案。然而产生的xml文件不太适合公司项目的规范。因此，想用模板的方式去实现
mybatis的代码生成器。这个代码参考ace-security的项目中代码生成器。

### 2. 如何使用

 -- 2.1  获取表列表
 
 http://localhost:7778/generator/page?limit=10&offset=0
 
 -- 2.2 生成代码
 
 http://localhost:7778/generator/page?limit=10&offset=0

### 3. 计划
