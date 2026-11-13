# book-admin

图书管理系统 · Spring Boot 后端

## 技术栈

- **语言**：Java 17
- **框架**：Spring Boot 3.2.5
- **ORM**：MyBatis-Plus 3.5.5
- **数据库**：MySQL 8.0
- **测试**：JUnit 5 + H2 内存数据库

## 功能

| 方法 | 路径 | 说明 |
|---|---|---|
| GET | `/api/books` | 分页查询（支持关键词搜索、分类筛选） |
| GET | `/api/books/{id}` | 查询图书详情 |
| POST | `/api/books` | 新增图书 |
| GET | `/api/books/ping` | 环境自测 |

## 项目结构
