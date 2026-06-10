# 云上3班 · AI 教学工具集

> **2026 年教师人工智能应用案例征集 · 创AI 案例**  
> AI 辅助开发的高中班级管理与学情分析一体化工具

[![Deploy to GitHub Pages](https://github.com/TeslaLiu-181/edu-ai-dashboard/actions/workflows/deploy.yml/badge.svg)](https://github.com/TeslaLiu-181/edu-ai-dashboard/actions/workflows/deploy.yml)

## 🎯 项目简介

这是一套由一线高中教师借助国产 AI 智能体（WorkBuddy）独立开发的班级管理工具集，包含两大核心模块：

| 模块 | 功能 | 技术栈 |
|------|------|--------|
| **云上3班教师看板** | 59人/9组全维度管理：座次图、积分中心、赛季公榜、考试备考 | TailwindCSS + Chart.js + SheetJS |
| **成绩追踪可视化** | 多场考试数据解析：均分趋势、排名双轴、六科雷达图、进退步热力图 | Chart.js + SheetJS |

## 🌐 在线演示

> **🔗 [https://teslaliu-181.github.io/edu-ai-dashboard/](https://teslaliu-181.github.io/edu-ai-dashboard/)**

## ✨ 核心特点

- **单文件架构**：每个工具均为独立 HTML 文件，无需安装部署
- **即开即用**：希沃一体机浏览器直接打开，数据保存在本地 localStorage
- **Excel 驱动**：拖入 Excel 表格即可自动解析数据，JSON 双向导入导出
- **AI 辅助开发**：全部代码通过 WorkBuddy AI 智能体辅助生成、调试、迭代
- **国产工具链**：使用国产 AI 平台与开源前端技术栈

## 🚀 快速开始

```bash
# 克隆仓库
git clone https://github.com/TeslaLiu-181/edu-ai-dashboard.git

# 直接用浏览器打开
open index.html
```

无需安装任何依赖，所有外部资源通过 CDN 加载（需联网）。

## 📦 项目结构

```
edu-ai-dashboard/
├── index.html           # 入口页面
├── dashboard.html       # 云上3班教师看板
├── score-tracker.html   # 成绩追踪可视化
├── .github/
│   └── workflows/
│       └── deploy.yml   # GitHub Pages 自动部署
└── README.md
```

## 🔧 部署说明

### GitHub Pages（推荐）

推送至 `main` 分支后，GitHub Actions 自动部署到 GitHub Pages：

1. Fork 或克隆本仓库
2. 在仓库 Settings → Pages 中选择 "GitHub Actions" 作为部署源
3. 推送代码，自动触发部署

### 本地使用

直接用浏览器打开 `index.html` 即可。所有工具均通过 CDN 加载依赖库（需要互联网连接）。

## 📄 申报信息

本项目参与 **2026 年教育部教育技术与资源发展中心（中央电化教育馆）教师人工智能应用案例征集活动**，申报类别为 **创AI 案例**（教师借助 AI 工具自主开发智能教育工具）。

## 📝 License

MIT

