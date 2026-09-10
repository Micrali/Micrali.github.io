# Chengran Li · Academic Homepage

李程然的个人学术主页，展示教育背景、研究工作、人工智能安全项目、竞赛经历与荣誉。

线上地址：<https://micrali.github.io/>

## 本地预览

这是一个零依赖静态站点。可以直接打开 `index.html`，或在项目根目录运行：

```powershell
python -m http.server 8000
```

然后访问 `http://localhost:8000`。

## 内容结构

- `index.html`：主页内容、SEO、Open Graph 与结构化数据
- `styles.css`：桌面端与移动端响应式视觉系统
- `script.js`：移动导航、滚动定位与渐入交互
- `CV_lcr_3page_v4.pdf`：主页提供下载的三页简历
- `docs/`：项目文档、投稿记录与获奖证明
- `assets/og.png`：社交平台分享预览图
- `robots.txt` / `sitemap.xml`：搜索引擎发现与索引配置

站点主色在 `styles.css` 顶部的 `:root` 变量中统一维护。

## 部署

仓库使用 GitHub 用户主页命名规则 `Micrali.github.io`。推送到 `main` 后，GitHub Pages 会从根目录自动发布。

可通过仓库的 `pages-build-deployment` 工作流确认发布状态。
