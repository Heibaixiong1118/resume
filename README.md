# 个人简历主页

一个单文件、可直接在浏览器打开的个人简历网页，面向 **AI Agent / 大模型应用开发** 方向，使用 GitHub Pages 托管。

- 在线访问：<https://heibaixiong1118.github.io/resume/>

## 特点

- **单文件自包含**：仅一个 `index.html`，样式全部内联，无任何框架与构建步骤，打开即用。
- **只读展示**：线上版本不可编辑，任何访客都无法修改页面内容。
- **响应式适配**：桌面、平板、手机均可正常浏览。
- **可打印 / 导出 PDF**：在浏览器中使用「打印 → 另存为 PDF」，即可得到一份排版良好的简历。

## 目录结构

```
.
└── index.html   # 简历页面（含全部样式）
```

## 本地预览

直接用浏览器打开 `index.html`；或在当前目录启动一个静态服务：

```bash
python -m http.server 8000
# 然后访问 http://localhost:8000
```

## 部署

仓库已开启 GitHub Pages，来源为 `main` 分支根目录。将更新后的 `index.html` 推送到 `main`，页面会在约一分钟内自动更新。

## 技术栈

HTML5 · 原生 CSS · 响应式布局 · GitHub Pages
