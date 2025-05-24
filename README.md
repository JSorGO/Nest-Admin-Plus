# Nest-Admin-Plus

## 📖 项目简介

Nest-Admin-Plus 是一个基于现代技术栈构建的企业级后台管理系统，致力于为开发者提供开箱即用的管理后台解决方案。项目采用前后端分离架构，后端使用 Node.js 生态中最优秀的企业级框架 Nest.js，前端基于 Vue 3 生态系统，打造高效、稳定、易维护的管理系统。

## ✨ 特性

- 🚀 **现代化技术栈**：基于 Nest.js + Vue 3 + TypeScript
- 🔐 **完善的权限系统**：支持多角色、多权限的细粒度控制
- 📱 **响应式设计**：适配桌面端、平板和移动端
- 🛡️ **类型安全**：全链路 TypeScript 支持
- 🎯 **开箱即用**：内置常用功能模块，快速启动项目
- ⚡ **高性能**：优化的构建配置和运行时性能
- 🔧 **高度可配置**：灵活的配置系统，满足不同业务需求

## 🛠️ 技术栈

### 后端技术
- **核心框架**：Nest.js - 基于 Node.js 的渐进式框架
- **语言**：TypeScript - 类型安全的 JavaScript 超集
- **数据库 ORM**：TypeORM / Prisma - 现代化数据库访问层
- **身份验证**：JWT + Passport - 安全的用户认证
- **API 文档**：Swagger - 自动生成接口文档
- **缓存**：Redis - 高性能缓存解决方案
- **验证**：Class-validator - 数据验证和转换
- **日志**：Winston - 结构化日志记录

### 前端技术
- **核心框架**：Vue 3 - 渐进式 JavaScript 框架
- **构建工具**：Vite - 下一代前端构建工具
- **UI 组件库**：Element Plus / Ant Design Vue - 企业级组件库
- **状态管理**：Pinia - Vue 3 官方推荐状态管理
- **路由**：Vue Router 4 - 官方路由解决方案
- **HTTP 客户端**：Axios - Promise 基的 HTTP 库
- **样式方案**：SCSS / Less - CSS 预处理器
- **代码规范**：ESLint + Prettier - 代码质量和格式化

## 🏗️ 系统架构

```
┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐
│   前端 (Vue3)   │───▶│  后端 (Nest.js) │───▶│   数据库 (MySQL) │
│                 │    │                 │    │                 │
│ • 用户界面      │    │ • API 服务      │    │ • 数据存储      │
│ • 状态管理      │    │ • 业务逻辑      │    │ • 数据关系      │
│ • 路由控制      │    │ • 权限控制      │    │                 │
└─────────────────┘    └─────────────────┘    └─────────────────┘
         │                       │                       │
         └───────────────────────┼───────────────────────┘
                                 ▼
                    ┌─────────────────┐
                    │   缓存 (Redis)   │
                    │                 │
                    │ • 会话存储      │
                    │ • 数据缓存      │
                    │ • 队列任务      │
                    └─────────────────┘
```

## 📦 功能模块

### 系统管理
- **用户管理**：用户信息维护、状态控制
- **角色管理**：角色权限配置、层级管理
- **菜单管理**：动态菜单配置、权限绑定
- **部门管理**：组织架构管理
- **字典管理**：系统字典数据维护
- **参数配置**：系统参数动态配置

### 系统监控
- **在线用户**：实时在线用户监控
- **操作日志**：用户操作行为记录
- **登录日志**：用户登录记录追踪
- **系统日志**：系统运行日志查看
- **服务监控**：系统性能指标监控

### 开发工具
- **代码生成**：基于模板的代码自动生成
- **API 文档**：在线接口文档
- **表单构建**：可视化表单设计器
- **定时任务**：计划任务管理

## 🚀 快速开始

### 环境要求
- Node.js >= 16.0.0
- npm >= 8.0.0 或 yarn >= 1.22.0
- MySQL >= 5.7 或 PostgreSQL >= 10
- Redis >= 5.0

### 安装部署

1. **克隆项目**
```bash
git clone https://github.com/your-username/nest-admin-plus.git
cd nest-admin-plus
```

2. **安装依赖**
```bash
# 后端依赖
cd backend
npm install

# 前端依赖
cd ../frontend
npm install
```

3. **配置环境**
```bash
# 复制环境配置文件
cp .env.example .env
# 编辑配置文件，设置数据库连接等信息
```

4. **启动服务**
```bash
# 启动后端服务
cd backend
npm run start:dev

# 启动前端服务
cd ../frontend
npm run dev
```

## 📱 预览

访问 `http://localhost:3000` 查看系统界面

默认管理员账号：
- 用户名：admin
- 密码：123456

## 📝 开发文档

- [项目结构说明](./docs/project-structure.md)
- [开发规范](./docs/development-guide.md)
- [API 接口文档](./docs/api-docs.md)
- [部署指南](./docs/deployment.md)

## 🤝 贡献指南

欢迎提交 Pull Request 或 Issue 来帮助改进项目。

1. Fork 本仓库
2. 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的修改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 打开一个 Pull Request

## 📄 许可证

本项目基于 MIT 许可证开源 - 查看 [LICENSE](LICENSE) 文件了解详情

## 🙏 致谢

感谢所有为这个项目做出贡献的开发者们！

---

⭐ 如果这个项目对您有帮助，请给我们一个 Star！
