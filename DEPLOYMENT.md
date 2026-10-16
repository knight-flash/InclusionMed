# InclusionMed GitHub Pages 发布

网站：https://knight-flash.github.io/InclusionMed/
仓库：https://github.com/knight-flash/InclusionMed

## 当前发布方式

使用 `main` 分支根目录的 `index.html` 发布静态网站。2026-10-16 检查时，线上页面与当时 `main/index.html` 完全一致，最近一次 Pages 部署成功。

仓库首页由 `README.md` 展示，Pages 网站由 `index.html` 展示，两者独立。本次合入新版网站 HTML，并撤下网页和中英文 README 中的旧 Logo；README 正文、共建指南和其他项目材料保留最新 main 内容。

## 更新页面

1. 将新的完整离线 HTML 命名为 `index.html`。本次内容来自 `index(3).html`，页面保留原有功能，仅将页眉和页脚 Logo 替换为纯文字 InclusionMed。
2. 将它上传到仓库 `main` 分支的根目录，替换原有 `index.html`。不要上传 ZIP 本身，也不要多套一层目录。
3. 保留根目录的空文件 `.nojekyll`，避免 Jekyll 转换静态内容。
4. 提交后打开仓库 Actions，等待 `pages build and deployment` 成功。
5. 打开网站并强制刷新，确认显示新的 InclusionMed Index 界面。

已有 Pages 配置无需重复修改。只有发布源被改动时，才需要进入 Settings → Pages，选择 `Deploy from a branch`、`main`、`/(root)` 并保存。

## 页面路由

本 HTML 已内置 CSS、JavaScript 和 Hash 路由，不需要 npm 构建，也不需要服务器重写规则。内部页面地址示例：

- 首页：https://knight-flash.github.io/InclusionMed/
- Mission：https://knight-flash.github.io/InclusionMed/#/mission
- Atlas：https://knight-flash.github.io/InclusionMed/#/atlas
- Methodology：https://knight-flash.github.io/InclusionMed/#/methodology
- Contribute：https://knight-flash.github.io/InclusionMed/#/contribute

直接使用 `/InclusionMed/atlas` 等路径不适用于此离线版本，请保留 `#/` 路由形式。

## 以后更新

替换根目录 `index.html` 并提交到 `main`，GitHub Pages 会自动重新发布。README 的修改不代替 HTML 网站的更新。

## 本次完整上传包

基于 GitHub main 提交 `779adb599d5025976d60e7358c0bf70d1e475560` 生成。解压后打开文件夹，选择里面的全部文件和 assets 文件夹，上传到仓库 main 根目录并替换同名文件；不要上传 ZIP 或外层文件夹。

Mac 可按 Command + Shift + . 显示 `.nojekyll` 隐藏文件。如网页上传未包含该空文件，可在仓库中用 Add file → Create new file 新建 `.nojekyll`。

## 对外链接

README 和共建指南中的 Website 入口统一指向公开的 https://knight-flash.github.io/InclusionMed/ 。内部页面使用 `#/mission`、`#/atlas` 等 Hash 路由；Resources 指向本仓库的 `assets/docs` 材料目录，不再使用内网预览站。
