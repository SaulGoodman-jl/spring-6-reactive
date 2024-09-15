# Spring Reactive 项目

## 项目简介
该项目基于Spring Reactive Web构建，使用反应式编程模型与非阻塞I/O，旨在处理高并发请求。它还集成了OAuth2资源服务器进行认证与授权，支持H2数据库的R2DBC（Reactive Relational Database Connectivity），并使用Spring Boot Actuator进行监控。

## 技术栈
- **框架**: Spring Reactive Web
- **数据库**: H2, Spring Data R2DBC
- **安全**: OAuth2 Resource Server
- **其他**: Lombok, Validation, Spring Boot Actuator

## 功能
1. **反应式API**：提供非阻塞的REST API。
2. **认证与授权**：集成OAuth2资源服务器，使用JWT进行验证。
3. **数据库支持**：通过Spring Data R2DBC与H2数据库交互，支持反应式数据库操作。
4. **应用监控**：使用Spring Boot Actuator暴露健康检查与性能指标。

## 安装步骤
1. 克隆项目：
   ```bash
   git clone https://github.com/SaulGoodman-jl/spring-6-reactive.git
   ```
2. 启动应用：
   ```bash
   .\mvnw spring-boot:run
   ```

## 配置
如需修改数据库或JWT验证配置，可在[application.properties](src/main/resources/application.properties)文件中调整相关内容。

## License
该项目基于MIT许可证，详见[LICENSE](./LICENSE)。