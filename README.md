# allen-dependencies

## 1. 说明
allen-dependencies为各工程的顶级工程，约定通用组件相关版本，统一开发过程中组件版本差异问题。
此工程不需要部署，只做为其它工程的顶级工程。

  版本不统一，存在以下问题：
 - 不同版本可能依赖的API变化，导致功能不兼容。
 - 不同版本导致漏洞修复困难，因为都是每个工程自己引用，这种分散
的依赖导致每个工程都得排查，调整依赖版本相对困难。
 - 错乱的依赖版本，可能引起jar冲突，如传递性依赖。

## 2. 目前约定的组件

|  name   | version    | remark |
|  ----  |------------| ----|
|  jdk  | 17         |  |
|  spring-boot  | 2.7.4      |     |
|  spring-cloud  | 2021.0.4   |     |
|  spring-cloud-alibaba  | 2021.0.4.0 |     |
|  druid-spring-boot-starter  | 1.2.12     |     |
|  dynamic-datasource-spring-boot-starter  | 3.5.2      |     |
|  redisson-spring-boot-starter | 3.17.5     |     |
|  mybatis-spring-boot-starter | 2.2.2      |  |
|  mybatis-plus-boot-starter | 3.5.2      |     |
|  xxl-job-core | 2.3.0      |     |
|  springfox-boot-starter | 3.0.0      |     |
|  guava | 31.0.1-jre |     |
|  shenyu | 2.5.0      |     |
|                              |            |     |