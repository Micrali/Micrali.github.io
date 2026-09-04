# io

个人学术主页的静态骨架，参考极简学术 portfolio 的信息结构设计，可直接部署到 GitHub Pages。

## 本地预览

这是一个零依赖静态站点。可以直接打开 `index.html`，或在项目目录运行：

```powershell
python -m http.server 8000
```

然后访问 `http://localhost:8000`。

## 后续替换清单

- `index.html`：姓名、简介、教育、研究、项目、荣誉与联系方式
- `assets/avatar-placeholder.svg`：替换为正式头像，并同步修改图片路径
- 简历文件：放入 `assets/`，再更新“下载简历”链接
- `styles.css`：如需修改主色，优先调整顶部 `:root` 中的颜色变量

## 部署

推送到 GitHub 后，在仓库 Settings → Pages 中选择 `Deploy from a branch`，分支使用 `main`，目录使用 `/ (root)`。
