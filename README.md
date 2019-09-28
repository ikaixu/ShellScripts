# Shell脚本注释
---
1. shell特性
2. shell变量
3. shell条件测试
4. shell数据运算
5. shell流程控制（if\case）
6. shell循环控制（for\while\until  break\continue\exit\shift）
7. shell数组（arry）
8. shell函数（function）
9. 企业面试题目
---
## 1.shell特性
### 1.1 login shell与nologin shell
```bash
# 切换到username用户，并且使用该用户的bash环境配置
su -username
# 切换到username用户，但是使用原用户的bash环境配置
su username
```
