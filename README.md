# static-site-test

一个用于测试 GitHub Pages 部署流程的极简个人主页。

## 技术栈

- 纯静态 HTML + CSS + 少量原生 JS
- 无构建工具、无依赖
- 由 GitHub Pages 免费托管

## 本地预览

直接双击 `index.html`，或用任意静态服务器：

```bash
python -m http.server 8000
# 然后打开 http://localhost:8000
```

## 部署

推送到 `main` 分支后，GitHub Pages 会自动构建并部署。

访问地址：https://gzytop.github.io/static-site-test/

## 文件结构

- `index.html` — 页面主体
- `styles.css` — 样式表
- `README.md` — 项目说明
