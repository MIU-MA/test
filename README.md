# 江西财经大学数智技术协会官方网站

## 项目简介

本项目是江西财经大学数智技术协会的官方网站，致力于为协会成员和广大同学提供信息交流平台。网站采用现代前端技术构建，展示协会活动、新闻动态、成员介绍等内容。

## 主要功能

- **协会介绍**：展示协会的历史、使命和活动。
- **新闻动态**：发布协会最新活动和公告。
- **成员展示**：介绍优秀成员和历届负责人。
- **响应式设计**：支持PC和移动端访问。
- **动画效果**：包含打字机、滚动动画等交互元素。

## 技术栈

- **前端框架**：Vue 3 (Composition API)
- **构建工具**：Vite
- **路由管理**：Vue Router 4
- **HTTP客户端**：Axios
- **样式**：CSS3 (支持动画和响应式布局)

## 安装与运行

### 环境要求

- Node.js 16+
- npm 或 yarn

### 安装依赖

```bash
npm install
```

### 开发模式运行

```bash
npm run dev
```

访问 `http://localhost:5173` 查看网站。

### 构建生产版本

```bash
npm run build
```

### 预览构建结果

```bash
npm run preview
```

## 项目结构

```
jxufe-dsa-site/
├── public/                 # 静态资源
│   └── images/            # 图片文件
├── src/
│   ├── assets/            # 样式和资源
│   ├── components/        # 可复用组件
│   ├── data/              # 数据文件
│   ├── router/            # 路由配置
│   ├── views/             # 页面视图
│   ├── App.vue            # 根组件
│   └── main.js            # 应用入口
├── index.html             # HTML模板
├── package.json           # 项目配置
├── vite.config.js         # Vite配置
└── README.md              # 项目说明
```

## 部署

项目构建后，可将 `dist/` 目录部署到静态网站托管服务，如GitHub Pages、Vercel或Netlify。

## 贡献指南

欢迎协会成员和开发者贡献代码。请遵循以下步骤：

1. Fork 本仓库
2. 创建功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

## 许可证

本项目采用 MIT 许可证。详见 [LICENSE](LICENSE) 文件。

## 联系我们

- **邮箱**：2117410945@qq.com
- **QQ群**：数智技术协会群 
- **官方网站**：https://jxufe-tech.top 

---

江西财经大学数智技术协会 © 2024
