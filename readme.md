## 介绍
用C++实现的reactor模式高并发WEB服务器

### 环境要求
* Linux
* C++14
* MySql

### 数据库配置
```bash
// 建立yourdb库
create database yourdb;

// 创建user表
USE yourdb;
CREATE TABLE user(
    username char(50) NULL,
    password char(50) NULL
)ENGINE=InnoDB;

// 添加数据
INSERT INTO user(username, password) VALUES('name', 'password');
```
### 服务器运行
```bash
make
./bin/server
```




