# 个人主页 · ccccongggg.github.io

> 智能制造工程本科在读 · 硬件 / 嵌入式 / 三维设计方向的线上个人站点，基于 Astro 静态生成，部署在 GitHub Pages / EdgeOne Pages。

![站点头像](assets/avatar-processed.png)

## 🔗 线上入口

| 页面 | 地址 | 内容 |
|---|---|---|
| 主页 | <https://ccccongggg.github.io> | 自我介绍、项目精选、技术栈与联系方式 |
| 简历 | <https://ccccongggg.github.io/resume.html> | 竞赛、认证与项目经历 |
| 知识库 | <https://ccccongggg.github.io/knowledge-base.html> | 学习与项目笔记索引 |
| 后台管理 | <https://ccccongggg.github.io/admin.html> | CMS 内容维护后台 |

## 📁 仓库内容

```
ccccongggg.github.io/
├── index.html            # 主页
├── resume.html          # 简历页
├── knowledge-base.html   # 知识库页
├── admin.html           # 在线内容管理后台
├── content.js            # 全站唯一内容数据源
├── assets/               # 头像、简历照片、样式与脚本构建产物
└── 404.html
```

## 🛠 技术与维护

- **技术栈**：Astro 5 静态站点 + Sveltia CMS 在线后台 + EdgeOne Pages / GitHub Pages 托管。
- **改内容**：优先在后台编辑，或直接修改 `content.js` 后重新构建发布。
- **重构版**：Vue 3 + Vite + TypeScript 重构源码在私有开发仓 `personweb`，线上静态站为本仓。

## 📌 状态

- ✅ 线上站点可访问，简历与项目内容已同步
- 🔄 Vue 3 重构版开发中，未替换线上版本
