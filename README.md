# Spring Overview Demo

Demo for Spring Overview

## 需求

实现一个 Web Application，对外提供一个获取用户信息的 API，请求 API 时返回用户信息（仅需返回固定的两条用户信息即可，内容如下）

请求样例：

```shell
# request
curl http://localhost:8080/api/users

# response
[{"id":1,"username":"Obama"},{"id":2,"username":"Clinton"}]  
```
