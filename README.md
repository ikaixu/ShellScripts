# Shell脚本注释
---
目录
1. [shell特性](#1.shell特性)
    - [1.1 login shell与nologin shell](##1.1-login-shell与nologin-shell)
    - [1.2 重定向](#1.2-重定向)
    - [1.3 命令排序](#1.3-命令排序)
    - [1.4 元字符](#1.4-元字符)
    - [1.5 颜色输出文本](#1.5-颜色输出文本)
2. [shell变量](#2.shell变量)
3. [shell条件测试](#3.shell条件测试)
4. [shell数据运算](#4.shell数据运算)
5. [shell流程控制（if\case）](#5.shell流程控制)
6. [shell循环控制（for\while\until  break\continue\exit\shift）](#6.shell循环控制)
7. [shell数组（arry）](#7.shell数组)
8. [shell函数（function）](#8.shell函数)
9. [企业面试题目](#9.企业面试题目)
---
## 1.shell特性
### 1.1 login shell与nologin shell
```bash
# 切换到username用户，并且使用该用户的bash环境配置
su -username
# 切换到username用户，但是使用原用户的bash环境配置
su username
```
运行shell的三种方式：  
1. 系统用户登录后默认运行的shell
2. 非登录交互式运行shell
3. 执行脚本运行非交互式shell
> 1. 当用户登录linux系统时候，Shell会作为登录的Shell启动，下面讨论这种方式的环境变量加载顺序。默认加载/etc/profile，执行/etc/profile.d下的脚本文件，加载~/.bash_profile，有~/.bashrc则加载无则跳过，找/etc/bashrc有则加载无则跳过。  
> 2. 非登录的shell，直接加载~/.bashrc，并且去加载/etc/bashrc。非登录shell中，设置环境变量在~/.bashrc中或者/etc/profile中，不在~/.bash_profile或者/etc/profile中。

### 1.2 重定向

### 1.3 命令排序

### 1.4 元字符

### 1.5 颜色输出文本
---
## 2.shell变量
## 3.shell条件测试
## 4.shell数据运算
## 5.shell流程控制
## 6.shell循环控制
## 7.shell数组
## 8.shell函数
## 9.企业面试题目