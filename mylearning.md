# 对于sql注入的入门：
### 1.“万能密码的应用”
#### 实质是利用了sql语句中的查询用户的账户，通过漏洞从而绕过账户密码从而注入进入网站。    

> 举例：
> a' or true #
> a' or 1=1 # 
> a' or 1=1 --+
### 对应着 username='a' or true \# 
### username='a' or true --+
---
## 在sql语句中\#以及--string--都是注释的关系
