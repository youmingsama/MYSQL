<p align="center">
  <a href="https://github.com/LiningZhu/database"><img src="https://img.shields.io/badge/阅读-read-brightgreen.svg" alt="阅读"></a>
</p>

### MYSQL期末自救笔记

### 目录

#### Awesome MySQL

- [21分钟MySQL基础入门](21-minutes-MySQL-basic-entry.md)
- [手册文档](awesome-mysql.md#手册文档) - 一些非官方的手册文档搜集
- [分析工具](awesome-mysql.md#分析工具) - 性能，结构和数据分析工具
- [GUI](awesome-mysql.md#gui) - 搜集的一些 MySQL 的客户端，也有命令行客户端
- [服务器](awesome-mysql.md#服务器) - MySQL服务器的衍生品
- [备份](awesome-mysql.md#备份) - 备份/存储/恢复 工具
- [官方资料](awesome-mysql.md#官方资料) - 官方的一些网站和文章
- [优秀文章](awesome-mysql.md#优秀文章) - 一些优秀的文章

#### 第1章 初识MySQL

- 1.1 [数据库基础](chapter1/1.1.md)
  - [什么是数据库](chapter1/1.1.md#什么是数据库)
  - [数据库分类](chapter1/1.1.md#数据库分类)
  - [数据库模型](chapter1/1.1.md#数据库模型)
  - [数据表](chapter1/1.1.md#数据表)
  - [关系键](chapter1/1.1.md#关系键)
- 1.2 [数据库技术构成](chapter1/1.2.md)
  - [数据库系统](chapter1/1.2.md#数据库系统)
  - [关系数据库基本概念](chapter1/1.2.md#关系数据库基本概念)
  - [SQL语言](chapter1/1.2.md#sql语言)
  - [数据库访问技术](chapter1/1.2.md#数据库访问技术)
- 1.3 [什么是MySQL](chapter1/1.3.md)
  - [MySQL介绍](chapter1/1.3.md#mysql-介绍)
  - [MySQL发展历史](chapter1/1.3.md#mysql-发展历史)
  - [MySQL版本](chapter1/1.3.md#mysql-版本)
  - [MySQL的优势](chapter1/1.3.md#mysql-的优势)
- 1.4 [如何学习MySQL](chapter1/1.4.md)

#### 第2章 MySQL的安装与配置

- 2.1 [Mac平台下安装与配置MySQL](chapter2/2.1.md)
  - [Mac上安装MySQL](chapter2/2.1.md#mac-安装mysql)
  - [Mac上卸载MySQL](chapter2/2.1.md#mac-卸载mysql)
- 2.2 [Centos 平台安装与卸载MySQL](chapter2/2.2.md)
  - [检查是否已安装](chapter2/2.2.md#检查是否已安装)
  - [更新安装源](chapter2/2.2.md#更新安装源)
  - [检查是否下载成功](chapter2/2.2.md#检查是否下载成功)
  - [查看版本](chapter2/2.2.md#查看版本)
  - [启动指定版本](chapter2/2.2.md#启动指定版本)
  - [安装MySQL](chapter2/2.2.md#安装mysql)
  - [查看安装目录](chapter2/2.2.md#查看安装目录)
  - [MariaDB切换MySQL](chapter2/2.2.md#mariadb切换mysql)
  - [卸载 MySQL 软件](chapter2/2.2.md#卸载-mysql-软件)
- 2.3 [Docker 安装 MySQL](chapter2/2.3.md)
  - [快速启动一个 MySQL 服务器实例](chapter2/2.3.md#快速启动一个-mysql-服务器实例)
  - [通过命令行访问 MySQL 容器](#通过命令行访问-mysql-容器)
  - [使用 MySQL 自定义配置文件](#使用-mysql-自定义配置文件)
  - [使用 stack 部署 MySQL](#使用-stack-部署-mysql)
- 2.4 [启动数据库设置初始密码](chapter2/2.4.md)
  - [命令行启动关闭重启MySQL服务](chapter2/2.4.md#命令行启动关闭重启mysql服务)
  - [图像界面启动关闭重启MySQL服务](chapter2/2.4.md#图像界面启动关闭重启mysql服务)
  - [查看初始密码](chapter2/2.4.md#查看初始密码)
  - [设置初始化密码](chapter2/2.4.md#设置初始化密码)
  - [启动报错处理](chapter2/2.4.md#启动报错处理)
- 2.5 [MySQL工具](chapter2/2.5.md)
  - [命令行使用程序](chapter2/2.5.md#命令行使用程序)
  - [MySQL Workbench客户端](chapter2/2.5.md#mysql-workbench客户端)
  - [常用图形管理工具](chapter2/2.5.md#常用图形管理工具)
  - [MyCli替代MySQL的mysql命令行工具](chapter2/2.5.md#mycli替代mysql的mysql命令行工具)
- 2.6 [MySQL配置修改](chapter2/2.6.md)
  - [MySQL安装目录说明](chapter2/2.6.md#mysql安装目录说明)
  - [配置文件的位置](chapter2/2.6.md#配置文件的位置)
  - [Windows系统配置文件读取](chapter2/2.6.md#windows系统配置文件读取)
  - [Linux系统配置文件读取](chapter2/2.6.md#linux系统配置文件读取)
  - [配置文件内容](chapter2/2.6.md#配置文件内容)

#### 第3章 数据库的基本操作

- 3.1 [连接数据库](chapter3/3.1.md)
  - [MySQL命令语法](chapter3/3.1.md#mysql命令语法)
  - [MySQL命令连接数据库](chapter3/3.1.md#mysql命令连接数据库)
  - [开启MySQL的远程帐号](chapter3/3.1.md#开启mysql的远程帐号)
  - [MySQL修改密码](chapter3/3.1.md#mysql修改密码)
- 3.2 [查看选择数据库](chapter3/3.2.md)
  - [查看数据库](chapter3/3.2.md#查看数据库)
  - [选择数据库](chapter3/3.2.md#选择数据库)
- 3.3 [创建数据库](chapter3/3.3.md)
  - [SQL语句创建数据库](chapter3/3.4.md#sql语句创建数据库)
  - [管理工具创建数据库](chapter3/3.4.md#管理工具创建数据库)
- 3.4 [删除数据库](chapter3/3.4.md)
  - [SQL语句删除数据库](chapter3/3.4.md#sql语句删除数据库)
  - [管理工具删除数据库](chapter3/3.4.md#管理工具删除数据库)
- 3.5 [数据库存储引擎](chapter3/3.5.md#)
  - [存储引擎简介](chapter3/3.5.md#存储引擎简介)
  - [常用引擎对比](chapter3/3.5.md#常用引擎对比)
  - [查看存储引擎](chapter3/3.5.md#查看存储引擎)
  - [设置存储引擎](chapter3/3.5.md#设置存储引擎)
  - [如何选择合适的存储引擎](chapter3/3.5.md#如何选择合适的存储引擎)

#### 第4章 数据表的基本操作

- 4.1 创建数据表

#### 第5章 数据类型和运算符

#### 第6章 MySQL函数

#### 第7章 查询数据

#### 第8章 插入、更新与删除数据

#### 第9章 索引

#### 第10章 存储过程和函数

#### 第11章 视图

#### 第12章 MySQL函数

#### 第13章 MySQL用户管理

#### 第14章 数据备份与还原

#### 第15章 MySQL日志

#### 第16章 性能优化

#### 第17章 各种问题解决

- [让MySQL支持emoji图标存储](chapter17/17.1.md)
- [Centos6下升级MySQL数据库](chapter17/17.2.md)
- [MySQL修改密码](chapter17/17.3.md)
  - [mysqld_safe不存在修改密码](chapter17/17.3.md#mysqld_safe不存在修改密码)
  - [启动修改丢失的mysql单实例root密码方法](chapter17/17.3.md#启动修改丢失的mysql单实例root密码方法)
  - [Mac下重置MySQL的root密码](chapter17/17.3.md#Mac下重置MySQL的root密码)
  - [不重启mysqld修改密码的方法](chapter17/17.3.md#不重启mysqld的方法)
- [Centos7 默认为MariaDB导致mysql安装不上](chapter2/2.2.md#centos7安装mysql)
- [mysql命令不存在](chapter2/2.1.md#mysql命令不存在)
- [MySQL服务启动失败解决方案](chapter2/2.3.md#linux-下命令操作)
- [密码不满足当前的策略要求导致无法开启远程帐号](chapter3/3.1.md#开启mysql的远程帐号)


## 

### 复习

- [基于复习资料中的判断题](docs/判断.md)
- [基于复习资料中的选择题](docs/选择.md)

## 参与贡献

如果你觉得我的笔记有什么需要改进的地方，欢迎发起 Pull Request。

如果有重大变化，请先打开一个 Issue，讨论您想要改变的内容。


## 开源许可证

[MIT License](./LICENSE "MIT License")

## 祝语

Happy Introduction to Databases, I hope you enjoy reading Databases as much as I do.


