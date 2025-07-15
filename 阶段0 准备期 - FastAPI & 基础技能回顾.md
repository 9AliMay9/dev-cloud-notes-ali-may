## 目标
- 本地开发环境搭建（WSL2 + Python + Docker + Git + VSCode）
- 掌握 FastAPI 核心机制：路由、请求处理、响应模型
- 理解依赖注入（Depends）基础
- 熟悉错误响应与状态码控制
- 初步了解 Dev 到 DevOps 的技能图谱
- 初始化 GitHub 仓库与 Obsidian 笔记结构

---

## FastAPI 核心机制

### 路由
- 使用 `@app.get()`, `@app.post()` 等装饰器定义接口路径
- 路径参数自动类型校验

### 请求与响应模型
- 使用 Pydantic `BaseModel` 定义请求与响应数据结构
- 通过 `response_model` 参数，指定接口响应格式，自动生成文档

### 依赖注入（Depends）
- 通过 `Depends()` 注入依赖项，如认证、数据库会话等
- 支持嵌套依赖，增强代码复用

### 错误响应与状态码
- 使用 `HTTPException` 返回错误，指定状态码和错误信息
- 使用 `status_code` 定义成功响应状态码，如 201 表示创建成功

---

## 进阶知识点简记

- Pydantic 的 `include` 和 `exclude` 用于精确控制返回字段，`dict()` 方法可结合使用
- 了解中间件基本概念，能插入请求/响应前后逻辑（如统计请求耗时）
- 初步理解 Dev → DevOps 技能图谱，后续深入学习容器、CI/CD、云平台等

---

## 环境与工具

- Git + GitHub：代码版本管理与远程仓库
- Obsidian：本地知识库，支持Markdown，高效笔记
- Docker（准备阶段了解，后续实操）

---

## 下一步计划

- 深入 FastAPI 依赖注入与异步特性
- 学习数据库 PostgreSQL + SQLModel/SQLAlchemy
- 实战任务管理项目：CRUD + 认证机制
- 搭建本地 Docker 环境，尝试容器化部署

---

*Ali May | 2025年7月15日*
