# static-site-test

gzy 的静态学习网站 —— 一个用来练手的单页静态站点，由 GitHub Pages 托管。

## 技术栈

- 纯静态 HTML + CSS + 一小段原生 JS
- 无构建工具、无依赖、无外部字体请求
- 由 GitHub Pages 免费托管

## 页面结构

整页是一张单页「纸」：左侧书脊、大字号刊头、两条分栏条目（关于 / 联系）、页脚。

- 字体只用系统字体栈：标题用宋体系衬线，正文用系统黑体
- 全站只有一个强调色（印刷蓝 `#1b3fa8`），只出现在交互状态上
- 入场动效为纯 CSS，且遵循 `prefers-reduced-motion`
- 页脚会显示本页加载时间（原生 JS，无依赖）

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
