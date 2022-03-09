# Chevereto 图床

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
