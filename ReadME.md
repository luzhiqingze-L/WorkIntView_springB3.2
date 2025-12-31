## 部署

### Tech Stack
- Spring Boot 3.2.0
- Spring Security 6
- Java 17

### APIs
- GET /hello (Basic Auth required)

### Test
curl -u test:123456 http://localhost:8080/hello

## 设计接口

```
POST /login
GET  /hello   (requires authentication)
```

认证方式：

- Username: test
- Password: 123456

## 配置 Spring Security

使用 `SecurityFilterChain`

### 推荐认证方式

- HTTP Basic

## 实现流程

### Step 1：创建 Controller

### Step 2：配置用户（内存用户）

### Step 3：SecurityFilterChain

## 本地验证（必须做）

`http://localhost:8080/hello`

- ### 登录访问

​	`# Hello World`