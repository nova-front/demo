# Demo演示

🎨 一个基于 React + TypeScript + Vite 构建的前端组件库演示项目，展示了 Nova Frontend 生态系统中的各种组件和工具。

## 📋 项目简介

这是一个演示项目，用于展示 Nova Frontend 组件库的功能和特性。项目包含了多个模块的演示，帮助开发者了解和使用我们的组件库。

### 🚀 主要功能

- **Base UI 组件库** - Headless UI 设计理念的无样式组件，提供最大的自定义灵活性
- **编辑器组件** - 功能丰富的文本编辑器组件，支持多种编辑模式和扩展
- **工具函数库** - 实用的工具函数集合，提升开发效率
- **EPV 数据展示** - 专业的数据可视化组件

### 🛠️ 技术栈

- **React 19** - 最新版本的 React 框架
- **TypeScript** - 类型安全的 JavaScript 超集
- **Vite** - 快速的前端构建工具
- **React Router 7** - 现代化的路由管理
- **ESLint** - 代码质量检查工具

## 🎯 组件特性

### Base UI 组件
- ✅ Headless UI 设计理念，完全无样式
- ✅ 支持多种 HTML 元素渲染（as 属性）
- ✅ 完整的 TypeScript 类型支持
- ✅ 无障碍功能支持（a11y）
- ✅ 键盘导航支持

### 编辑器组件
- ✅ 基础文本编辑功能
- ✅ EPV 数据展示模式
- ✅ 可扩展的编辑器架构
- ✅ 响应式设计

## 🚀 快速开始

### 环境要求

- Node.js >= 18
- npm 或 pnpm

### 安装依赖

```bash
npm install
# 或
pnpm install
```

### 启动开发服务器

```bash
npm run dev
# 或
pnpm dev
```

访问 [http://localhost:5173](http://localhost:5173) 查看演示。

### 构建生产版本

```bash
npm run build
# 或
pnpm build
```

### 预览生产构建

```bash
npm run preview
# 或
pnpm preview
```

## 📦 项目结构

```
src/
├── components/          # 公共组件
│   ├── Layout.tsx      # 布局组件
│   └── DemoSection.tsx # 演示区块组件
├── pages/              # 页面组件
│   ├── home/           # 首页
│   ├── base-ui/        # Base UI 演示页
│   └── editor/         # 编辑器演示页
├── styles/             # 样式文件
└── router.tsx          # 路由配置
```

## 🌐 在线演示

项目已部署到 GitHub Pages，可以通过以下链接访问：

[🔗 在线演示地址](https://your-username.github.io/demo/)

> 注意：请将上述链接中的 `your-username` 替换为实际的 GitHub 用户名。

## 📚 使用指南

### 导航说明

- **首页** - 项目概览和功能介绍
- **Base UI** - Headless UI 组件演示，包含按钮组件的各种用法
- **编辑器** - 文本编辑器和 EPV 数据展示功能

### 组件使用示例

```tsx
import { Button } from '@nova-fe/base-ui';

function App() {
  return (
    <Button
      className="btn btn-primary"
      onClick={() => console.log('点击了按钮')}
    >
      点击我
    </Button>
  );
}
```

## 🚀 部署

项目配置了 GitHub Actions 自动部署工作流，当代码推送到 `main` 或 `master` 分支时会自动构建并部署到 GitHub Pages。

## 🤝 贡献指南

1. Fork 本仓库
2. 创建特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启 Pull Request

## 📄 许可证

本项目仅用于演示目的。

## 🔧 开发说明

### 代码规范

项目使用 ESLint 进行代码质量检查：

```bash
npm run lint
```

### 类型检查

项目使用 TypeScript 进行类型检查，构建时会自动进行类型验证。

---

**Nova Frontend 组件库演示项目** - 展示现代化前端组件库的最佳实践 🎨
