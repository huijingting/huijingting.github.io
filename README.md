# huijingting 的博客

基于 Hugo + PaperMod 主题，通过 GitHub Actions 自动部署到 GitHub Pages。

## 本地不需要装任何东西

写文章只需要编辑 `content/` 目录下的 Markdown 文件，然后提交推送。GitHub Actions 会自动安装 Hugo、拉取主题、构建并部署。

## 写新文章

在 `content/posts/` 下新建 `.md` 文件：

```markdown
---
title: "文章标题"
date: 2026-11-25
description: "文章描述"
tags: ["标签1", "标签2"]
categories: ["分类"]
---

正文内容...
```

然后执行：

```bash
git add .
git commit -m "添加新文章"
git push
```

几分钟后访问 https://huijingting.github.io 即可看到。

## 想在本地预览（可选）

如果想本地预览效果，需要安装 Hugo Extended：

```bash
# 拉取主题
git clone --depth 1 https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod
# 启动预览服务器
hugo server
```

浏览器打开 http://localhost:1313 查看。

## 自定义

编辑 `hugo.toml` 可修改站点标题、描述、菜单等配置。
