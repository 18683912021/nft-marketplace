# NFT 数字藏品

一个基于 React + Vite 的 NFT 数字藏品展示平台,支持钱包连接、藏品浏览与铸造(模拟)等功能。

## 技术栈

- **React 18** — UI 框架
- **Vite 4** — 构建工具
- **Framer Motion** — 交互动画
- **Canvas** — 粒子效果(自定义实现)

## 功能特性

- 🔑 钱包连接登录(带连接步骤反馈与错误提示)
- 🏠 首页 Hero 展示区(数字统计动画)
- 🖼️ NFT 藏品网格展示与详情弹窗
- ✨ 铸造(Mint)弹窗与成功彩带特效
- 🔔 Toast 全局消息提示
- 🌌 粒子背景动画

## 快速开始

```bash
# 安装依赖
npm install

# 启动开发服务器(默认 http://localhost:3000)
npm run dev

# 生产构建
npm run build

# 本地预览构建产物
npm run preview
```

## 项目结构

```
src/
├── components/        # 页面组件(Header、Hero、NFTGrid、MintModal 等)
├── hooks/             # 自定义 Hook(useWallet、useCountUp)
├── App.jsx            # 应用入口
├── main.jsx           # React 挂载入口
└── index.css / App.css  # 全局与组件样式
```

## 说明

- 本项目为前端展示用途,钱包连接与铸造为模拟实现,仅作演示。
- 开发服务器配置为 `host: 0.0.0.0`,可通过局域网访问。
