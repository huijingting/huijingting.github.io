---
title: "Hello, Hugo!"
date: 2026-11-24
description: "我的第一篇博客文章，记录博客搭建过程。"
tags: ["Hugo", "GitHub Pages", "博客"]
categories: ["随笔"]
---

## 欢迎来到我的博客

这是使用 **Hugo + PaperMod + GitHub Pages** 搭建的第一篇文章。

## 这个博客是怎么来的

- 内容用 Markdown 编写，存放在 `content/` 目录
- 每次 push 到 GitHub，Actions 会自动安装 Hugo、构建静态站点并部署
- 完全免费，无需服务器，无需本地安装 Hugo

## 怎么发新文章

在 `content/posts/` 目录下新建一个 `.md` 文件，写上标题和日期：

```markdown
---
title: "文章标题"
date: 2026-11-25
tags: ["标签"]
---

正文内容写在这里。
```

然后 `git add` + `git commit` + `git push`，几分钟后就能在网站上看到。

享受写作吧！
