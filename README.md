
# Spring Data JPA

## 环境

- 代码在 `src/test/java/com/example/employee/` 目录和 `src/main/java/com/example/employee/` 目录
- 本地运行，需要启动 `MySQL` 并创建数据库`employee_db` 
- MySQL 默认的用户名和密码都是 root，本地运行需要修改文件 `src/main/resources/application.yml` 和 `src/test/java/com/example/employee/EmployeeJPATest.java` 中的密码


## 运行测试

在根目录下执行 `./gradlew test` 显示 `BUILD SUCCESSFUL` 说明所有通过测试。


-----

> # Spring Data JPA
> 
> ## 练习描述
> 
> 本题要求使用 `Spring Data JPA` 来操作实体对象`Company`,`Employee`，实现对数据库的 `CRUD (增删改查)` 操作。
> - 要求使用 `Flyway Core` 对数据库做版本控制
> - 完成题目需求使得测试全部通过
> 
> #### note:
> - 请不要修改项目中mysql的用户名和密码，否则测试不通过！
> 
> ## 环境要求
> - java8
> - Intellij-IDEA
> 
> ## 如何开始
> - 克隆模版库
> - 本地启动 `MySQL` 
> - 搭建数据库`employee_db`
> - 在`build.gradle`中添加 `Spring Data JPA` 以及 `Flyway Core` 等依赖
> - 根目录下执行 `./gradlew test` ，此时测试都是失败的
> - 开始在`main`下的`entity`中创建实体
> - 开始在`main`下的`repository`中完成实现
> - 开始在`test`下的`EmployeeJPATest`中完成测试
> 
> ## 如何测试
> - 根目录下执行`./gradlew clean test`，查看测试结果
> 
> ## 输出规范
> - 完成需求的代码和测试
