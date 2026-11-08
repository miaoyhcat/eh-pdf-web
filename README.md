# E-Hentai 画廊转 PDF 的网页（静态前端）

一个纯静态页面，托管在 GitHub Pages。页面把请求发给自建服务器上的后端，
由后端抓图、合成 PDF、提供在线阅读。

## 用

https://miaoyhcat.github.io/eh-pdf-web/

- **下载 / 转 PDF**：贴 e-hentai / exhentai 画廊链接，或 JM 号（`jm1454202` / `1454202`）
- **搜索**：选平台（禁漫 / E-Hentai）+ 按作品名或作者名，搜到后一键转 PDF
- **在线阅读**：任务完成后点「在线阅读」，站内翻页看，无需下载

## 说明

- `config.js` 里是后端地址，后端换了只改这一行
- 纯 HTML + 原生 JS，无框架无构建
- 后端不在这个仓库里，源码私有
