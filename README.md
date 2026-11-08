# E-Hentai → PDF（网页版）

一个纯静态页面，把画廊链接发给后端服务器，后端抓图合成 PDF。
页面本身托管在 GitHub Pages，后端在自己的服务器上，源码不开源。

## 用

打开 https://miaoyhcat.github.io/eh-pdf-web/ ，粘贴 e-hentai / exhentai 画廊链接，点「开始生成」，
完成后点「下载 PDF」。

## 说明

- `config.js` 里是后端地址，换了隧道/域名只改这一行
- 页面无框架、无构建，纯 HTML + 原生 JS
