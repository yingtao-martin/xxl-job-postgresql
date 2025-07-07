# xxl-job-postgresql 2.4.1

## 2.4.1-RELEASE
### 基于官方2.4.1-SNAPSHOT版本改进而来，实现对postgresql数据库的支持

### 新增
#### 对postgresql 4.2.23版本的支持

### 更新
#### xxl-job-admin模块下资源resources目录下的mybatis-mapper目录下的8个xml文件的postgresql语法的优化支持
#### application.properties文件的postgresql数据源配置，配置如下：

```
spring.datasource.url=jdbc:postgresql://10.32.31.15:5432/xxl_job
spring.datasource.username=postgres
spring.datasource.password=WL-U@=Nj75SHin
spring.datasource.driver-class-name=org.postgresql.Driver
```