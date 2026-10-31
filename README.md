# Astro 个人博客模板

干净、极简的 Astro 博客模板，适合个人站点。

## 快速开始

```bash
cd astro-blog
npm install
npm run dev
```

打开 http://localhost:4321 查看。

## 写文章

在 `src/content/blog/` 目录下新建 `.md` 文件即可。

示例 frontmatter：

```md
---
title: "文章标题"
description: "简短描述"
date: 2026-10-31
tags: ["标签1", "标签2"]
draft: false
---

正文内容...
```

## 部署

推荐使用 Cloudflare Pages 或 Vercel：

- Build command: `npm run build`
- Output directory: `dist`

## 自定义

- 修改 `src/layouts/Layout.astro` 调整整体布局
- 修改 `src/styles/global.css` 调整样式
- 在 `astro.config.mjs` 中修改 `site` 为你的域名
