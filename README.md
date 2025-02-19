<p align="center">
  <img src="public/logo.svg" width="100" height="100" alt="Status Monitor Logo">
</p>

<h1 align="center">站点监测</h1>

<p align="center">优雅的站点状态监控面板</p>

<p align="center">
  <img src="https://img.shields.io/badge/Vue.js-3.5-4FC08D?logo=vue.js" alt="Vue">
  <img src="https://img.shields.io/badge/Tailwind_CSS-3.4-38B2AC?logo=tailwind-css" alt="Tailwind">
  <img src="https://img.shields.io/badge/license-MIT-blue.svg" alt="License">
</p>

## 📖 简介

站点监测是一个基于 UptimeRobot API 开发的站点状态监控面板，支持多站点状态监控、实时通知、故障统计等功能。界面简洁美观，响应式设计，支持亮暗主题切换。

## ✨ 功能预览

![功能预览](https://i1.wp.com/dev.ruom.top/i/2025/01/25/629114.webp)

## ✨ 特性

- 📊 实时监控：支持多种监控方式
- 📱 响应式设计：适配移动端和桌面端
- 🌓 主题切换：支持亮色/暗色主题
- 📈 数据统计：可视化展示可用率和响应时间
- 🔔 故障记录：详细的宕机记录和原因分析
- 🔄 自动刷新：定时自动更新监控数据
- 💫 平滑动画：流畅的用户界面交互体验

## ⚙️ 部署配置

### 环境要求

- Node.js >= 16.16.0
- NPM >= 8.15.0 或 PNPM >= 8.0.0

### 获取 UptimeRobot API Key

1. 注册/登录 [UptimeRobot](https://uptimerobot.com/)
2. 进入 [Integrations & API](https://dashboard.uptimerobot.com/integrations)
3. 下拉到最底部在 Main API keys 部分创建 **Read-Only API Key**
4. 复制生成的 API Key

### API 代理说明

本项目支持以下三种部署方式,均可实现自动处理跨域请求:

1. **腾讯云 EdgeOne Pages**
   - 点击上方蓝色 "Deploy" 按钮
   - 连接到GitHub，选择项目
   - 框架预设选择Vue，点击开始部署
   - 使用默认配置 `VITE_UPTIMEROBOT_API_URL = "/api/status"`

2. **Vercel**
   - 点击上方黑色 "Deploy" 按钮
   - 连接到GitHub，选择项目
   - 填写项目名称，点击Create
   - 使用默认配置 `VITE_UPTIMEROBOT_API_URL = "/api/status"`

3. **Cloudflare Pages**
   - 点击上方橙色 "Deploy" 按钮
   - 找到计算(worker) 部分
   - 点击创建，选择Pages，连接到GitHub，选择项目，点击开始创建
   - 框架预设选择Vue，点击保持并部署
   - 使用默认配置 `VITE_UPTIMEROBOT_API_URL = "/api/status"`

4. **其他平台**
   - 自行搭建 API 代理
   - 在 `.env` 文件中设置 `VITE_UPTIMEROBOT_API_URL` 为你的 API 代理地址

## 📝 开源协议

本项目基于 [MIT License](LICENSE) 开源，使用时请遵守开源协议。

## 🙏 致谢

- [UptimeRobot](https://uptimerobot.com/) - 提供监控 API 支持
- [Vue.js](https://vuejs.org/) - 前端框架
- [Tailwind CSS](https://tailwindcss.com/) - CSS 框架
- [Chart.js](https://www.chartjs.org/) - 图表库 
