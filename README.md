# 🌌 Clay-SpaceStation (星壤空间站)

![Version](https://img.shields.io/badge/Version-2.0_Alpha-blue)
![License](https://img.shields.io/badge/License-COSL_v1.0-orange)
![React](https://img.shields.io/badge/React-18.x-61dafb?logo=react)
![TailwindCSS](https://img.shields.io/badge/Tailwind-CSS-38bdf8?logo=tailwindcss)

**Clay-SpaceStation** 是一个以“星际护照”和“空间站”为主题的个人展示页/引导页。本项目由 **Claylark (星壤云雀)** 开发，采用高度定制化的 UI 设计，旨在以极具沉浸感的方式展示个人档案、兴趣图谱、社交网络和项目经历。

## ✨ 核心特性 (Features)

* 🌍 **智能多语言路由**: 根目录自带语言检测脚本，能够根据浏览器语言自动重定向至简体中文、繁体中文或英文版本。
* 🌗 **自适应深色模式**: 支持跟随系统主题自动切换，并提供手动切换按钮。
* 🎫 **创意护照 UI**: 桌面端采用 1:1 ICAO 标准护照矢量布局，支持动态生成当前签发日期。
* 📱 **完美响应式交互**: 基于 Tailwind CSS 适配所有尺寸设备，并引入了 `scroll-snap` 全屏滚动效果。
* 🤖 **内置 AI 助手 (ClaySeek)**: 集成了液态玻璃风格的 AI 聊天悬浮窗前端 UI。

## 🛠️ 技术栈 (Tech Stack)

本项目采用了**无构建 (Build-less)** 的纯前端单文件架构：
* **核心框架**: React 18 (通过 UMD 引入) + Babel Standalone。
* **样式方案**: Tailwind CSS (通过 CDN 引入)。
* **字体与图标**: Google Sans Flex, Noto Sans, 以及 Material Symbols Rounded。

``` 📂 目录结构 (Structure)

Clay-SpaceStation/
├── index.html          # 根目录入口，负责语言检测与路由分发
├── zh-CN/
│   └── index.html      # 简体中文版主页
├── zh-HK/
│   └── index.html      # 繁体中文版 (香港/澳门)
├── zh-TW/
│   └── index.html      # 繁体中文版 (台湾)
├── en-US/
│   └── index.html      # 英文版主页
├── License.md          # COSL 开源使用许可协议文件
└── README.md           # 项目说明文档
```

## 🚀 如何使用与部署 (Usage & Deployment)

本项目不需要执行任何安装命令。

1. **本地预览**: 直接在浏览器中打开任何文件夹下的 `index.html` 即可预览。
2. **启用 AI 助手**: 在对应语言的 `index.html` 中找到 `apiKey` 变量并填入你的 Google Gemini API Key 即可激活聊天功能。
3. **线上部署**: 将整个仓库上传至 GitHub Pages、Vercel 或任何静态托管平台即可运行。

## 📄 开源协议说明 (License)

本项目采用创作者自定义的 **Claylark Open Source License (COSL) v1.0**。

**协议核心要点：**
* **非商业使用**: 允许个人学习、学术研究或公益慈善目的的使用。
* **禁止商用**: 严禁未经书面授权的任何商业化变现行为。
* **标识保留**: 严禁移除 Claylark 著作权标识。
* **反向授权**: 衍生作品默认授予原始权利人将改进部分整合至主分支的权利。
* **特定主体排除**: 协议第十一条明确**永久排除特定自然人 (薛楚涵)** 获得任何授权。

## 📬 联系作者 (Contact)

* **作者**: Claylark (星壤云雀)
* **邮箱**: clay@claylark.com 或 me@claylark.com
* **GitHub**: [@Claylark](https://github.com/Claylark)

---
*愿此行，终抵群星 | May this journey lead us starward.*
