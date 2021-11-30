docker run -d --name nacos -p 8848:8848 -e PREFER_HOST_MODE=hostname -e MODE=standalone nacos/nacos-server





```bash
# mysql配置
spring.datasource.platform=mysql
db.num=1
db.url.0=jdbc:mysql://101.34.238.174:3306/nacos_config?characterEncoding=utf8&connectTimeout=1000&socketTimeout=3000&autoReconnect=true&serverTimezone=UTC
db.user=root
db.password=admin
```

