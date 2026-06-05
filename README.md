# GitHub Pages 发布说明

这个目录已经整理成可直接用于 GitHub Pages 的静态站点。

## 目录说明

- `index.html`
  - 默认首页，当前指向今天的正式晨报内容
- `ai-morning-brief-latest.html`
  - 固定入口，适合每天发群
- `ai-morning-brief-2026-06-05.html`
  - 当天归档版
- `assets/`
  - 页面依赖的静态资源
- `.nojekyll`
  - 防止 GitHub Pages 误处理静态文件

## 最短发布步骤

1. 新建一个 GitHub 仓库，比如 `ai-morning-brief`
2. 把这个目录下的全部文件上传到仓库根目录
3. 在 GitHub 仓库里打开：
   - `Settings`
   - `Pages`
   - `Build and deployment`
   - `Source` 选择 `Deploy from a branch`
   - 分支选 `main`
   - 文件夹选 `/ (root)`

保存后，GitHub 会给你一个公网地址，通常形如：

- `https://<你的用户名>.github.io/ai-morning-brief/`

## 访问建议

- 发群时优先发固定入口：
  - `https://<你的用户名>.github.io/ai-morning-brief/ai-morning-brief-latest.html`
- 如果你希望默认首页永远打开最新一期，也可以直接发：
  - `https://<你的用户名>.github.io/ai-morning-brief/`
