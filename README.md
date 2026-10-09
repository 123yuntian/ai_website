# ai_website

我的第一个个人主页。纯静态站点，没有构建步骤，没有依赖。

## 本地预览

直接用浏览器打开 `index.html` 即可。

若想用本地服务器（推荐，避免部分浏览器对 `file://` 的限制）：

```bash
python -m http.server 8000
# 然后访问 http://localhost:8000
```

## 目录结构

| 路径 | 作用 |
|---|---|
| `index.html` | 页面结构与内容 |
| `style.css` | 全部样式 |
| `script.js` | 交互逻辑 |
| `assets/` | 图片等静态资源 |

## 贡献

欢迎提 Issue 讨论想法，动手前请先开分支并通过 PR 提交。
