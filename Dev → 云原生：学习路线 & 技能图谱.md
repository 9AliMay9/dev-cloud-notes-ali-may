起始时间：2025-07-11  
目标：大三下 / 明年暑假 / 秋季获得第一份实习  
主线方向：Python 后端开发 → 工程部署 → 云原生 / DevOps → 平台工程/高阶运维/云架构师

---

## 分阶段 & 每月任务

### 阶段 0：准备期（2025年7月）

- 配置本地开发环境（WSL2 + Python + Docker + Git + VSCode）
- 学习 FastAPI 核心机制（路由 / 请求处理 / 响应模型）
- 熟悉 GitHub 项目管理（Issues / Project / README / License）
- 初始化 Obsidian 学习笔记与 GitHub 学习型仓库
- 梳理 Dev → DevOps 整体技能图谱
- 熟悉 Linux CLI 操作与基础服务概念（ssh / systemctl / 文件权限）

---

### 阶段 1：后端开发基础（2025年8月）

- 掌握 FastAPI 的依赖注入 / 中间件 / 异步特性
- 系统学习 PostgreSQL + SQLAlchemy（同步 + 基础异步用法）
- 完成实战项目：任务管理 API 系统（CRUD + Token认证）
- 掌握 OAuth2 + JWT 身份认证机制
- 初步了解 RESTful API 设计风格与接口文档编写（Swagger / Redoc）
- 每日练习 1~2 个 LeetCode Easy/Medium 后端题
- 学习 Python 高阶特性（生成器 / 装饰器 / 上下文管理器）
- 了解项目结构组织与虚拟环境/依赖管理（Poetry / PDM）

---

### 阶段 2：工程部署基础（2025年9月）

- 使用 Docker 构建 FastAPI 镜像 + Compose 组织服务结构
- 学习 Nginx + Uvicorn / Gunicorn 的生产部署流程
- 掌握 Linux 常用命令 + 服务管理（systemd / ssh / firewall）
- 实战部署任务管理系统到远程 VPS
- 学习 Shell 脚本基础（参数 / 条件判断 / 循环）用于简化部署流程
- 引入监控基础（top / htop / journalctl / netstat）

---

### 阶段 3：CI/CD 与测试（2025年10月）

- 学习 pytest + coverage 进行单元/集成测试
- 掌握 GitHub Actions：实现自动测试 + 自动部署流程
- 撰写完整项目文档（README / 接口文档 / 使用说明）
- 了解代码质量工具链（lint / pre-commit / formatter / CI badge）
- 学习 Markdown / Mermaid / PlantUML 绘图用于架构描述
- 实践团队协作中的 Issue 管理与 Release Tagging

---

### 阶段 4：云原生入门（2025年11月）

- 学习 Kubernetes 核心组件：Pod / Deployment / Service / ConfigMap
- 使用 minikube/k3s 搭建本地集群并部署 FastAPI 服务
- 引入 Ingress Controller 进行服务暴露与路径路由
- 学习 Helm 并使用模板化部署项目
- 初步接触 Prometheus + Grafana 监控 FastAPI 服务
- 掌握容器日志采集与查看（kubectl logs / stdout JSON logging）
- 理解容器调度 / 挂载卷 / 环境变量等与平台相关的能力基础

---

### 阶段 5A：云平台实践（2025年12月）

- 掌握 AWS 核心服务：EC2 / S3 / IAM / VPC / CloudWatch
- 使用 Terraform 实现基础设施部署（IaC 实践）
- 熟悉云厂商 CLI / SDK 工具链，实现资源管理自动化
- 实战将完整 FastAPI + PostgreSQL 项目部署至 AWS/GCP
- 理解网络策略、安全组、防火墙等云平台安全实践
- 学习多账号/权限策略设计，初步接触 DevSecOps 思维

---

### 阶段 5B：平台视角与差异化能力强化（2026年1月）

- 梳理平台工程核心理念：可复用 / 自动化 / 高可观测性
- 了解平台团队职责（提供标准化工具链与工程基础设施）
- 结合自身项目引入日志统一格式（结构化 JSON）、部署规范（Helm Chart）
- 探索云原生可观测性最佳实践（Prometheus Rule / Alert / Dashboard）
- 整合 Dev → DevOps → Platform 的完整学习路径，形成系统化知识输出（如制作 Notion 项目页 / 知识地图）

---

### 阶段 5C：简历准备与模拟投递（2026年2月）

- 编写中英文简历，突出系统性成长路径与差异化能力
- 优化 GitHub 项目主页：高亮文档 / 交互式接口 / 流程图 / Badge
- 撰写项目介绍文档与中英文技术博客（以实战映射岗位能力）
- 准备模拟面试：项目讲解 / HTTP / SQL / 云部署场景题
- 梳理实习岗位 JD，制定差异化“信息差”能力呈现策略
- 整理并练习行为面试 STAR 框架（协作 / 问题解决 / 自主学习）

---

## 技能图谱（模块拆解）

### 后端开发基础（Dev）

- Python 高级语法（生成器、装饰器、上下文管理器）
- FastAPI：路由、依赖注入、中间件、响应模型
- SQL 与 ORM：SQLAlchemy（同步 + 基础异步）、SQL 语法
- 数据库设计：建模范式 / 事务与索引 / 外键关联
- 身份认证：OAuth2 + JWT
- RESTful API 设计规范与接口文档生成
- 项目结构组织与依赖管理（Poetry / PDM）

---

### 工程部署实践

- Git & GitHub：分支管理（Git Flow）、Rebase 与合并
- Docker：镜像构建、容器编排（Compose）、Volume 挂载
- Shell 脚本：流程控制 / 部署脚本化
- Nginx + Gunicorn/Uvicorn 生产部署流程
- CI/CD：GitHub Actions 自动测试与部署
- pytest + coverage + 质量控制工具链（黑盒测试 + lint + pre-commit）
- Markdown / PlantUML / Mermaid 绘图与文档撰写

---

### 云原生技术栈（DevOps）

- Kubernetes：Pod / Deployment / Service / ConfigMap / Ingress
- Helm：Chart 模板化部署
- 监控体系：Prometheus + Grafana + CloudWatch 入门
- 云平台：AWS/GCP 关键服务（EC2 / S3 / IAM / VPC / SDK）
- 日志采集与可视化：stdout JSON logs / Ingress logs
- IaC：Terraform 编写和管理基础设施
- 自动化运维工具与平台协作视角（Platform Engineering 思维）