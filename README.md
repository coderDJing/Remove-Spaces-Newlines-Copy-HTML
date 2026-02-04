# Remove-Spaces-Newlines-Copy-HTML

## 状态
- 已将桌面上的 `trim-copy.html` 复制为仓库根目录 `index.html`
- 已添加 GitHub Actions 工作流用于自动部署 GitHub Pages

## 部署说明
- 站点入口文件：`index.html`
- 工作流：`.github/workflows/deploy-pages.yml`
- 首次需要在仓库 Settings → Pages 中把 Source 设为 “GitHub Actions”
- 推送到 `main` 分支会自动部署（如果你的默认分支不是 `main`，请修改工作流分支）
