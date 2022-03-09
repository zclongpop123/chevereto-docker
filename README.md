# Chevereto 图床
克隆仓库
```bash
https://github.com/zclongpop123/chevereto-docker.git
```
启动容器
```bash
docker-compose up -d
```
创建数据库
```bash
CREATE DATABASE chevereto_db;
```
创建数据库用户
```bash
CREATE USER chevereto_db_user;
```
授予数据库用户权限
```bash
GRANT ALL ON chevereto_db.* TO chevereto_db_user;
```
设置数据库用户密码
```bash
set password for chevereto_db_user=password("zcl.123");
```
