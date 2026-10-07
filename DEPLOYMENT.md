# 在 knight-flash/InclusionMed 发布项目主页

仓库：https://github.com/knight-flash/InclusionMed

启用 GitHub Pages 并发布成功后，默认项目主页地址为：

**https://knight-flash.github.io/InclusionMed/**

中文入口：**https://knight-flash.github.io/InclusionMed/index.zh-CN.html**

这两个地址是预期发布地址，当前尚未启用发布。仓库里的 README 是 GitHub 上直接阅读的项目介绍；`index.html` 是网站首页。页面已生成，发布不需要安装工具或执行构建。

## 第一步：上传文件

1. 用 **knight-flash** 账号登录 GitHub，打开仓库。
2. 点击 **Add file → Upload files**。
3. 解压发布包，打开解压后的文件夹，将里面的文件和 `assets` 文件夹一起拖到上传区域。不要上传 ZIP 本身，也不要把整个外层文件夹作为一级目录上传。
4. 确认 `index.html`、`index.zh-CN.html`、`README.md` 和 `assets/` 都位于仓库根目录。原有 `LICENSE` 保留即可，上传包没有修改它。
5. 在提交说明中填写 `Add InclusionMed project homepage`，提交到 `main`。

`.nojekyll` 是隐藏文件，用于跳过 Jekyll 处理。如果文件选择器未显示它，核心 HTML、CSS 和材料仍可先上传；后续可再通过新建文件添加这个空文件。

## 第二步：启用 Pages

打开 https://github.com/knight-flash/InclusionMed/settings/pages

在 **Build and deployment** 下选择：

- **Source**：`Deploy from a branch`
- **Branch**：`main`
- **Folder**：`/(root)`

点击 **Save**。发布进度可以在 **Actions** 中查看；完成后，Pages 设置页会显示实际网站地址。

[GitHub Pages 官方配置说明](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

## 第三步：检查发布结果

1. 打开 Pages 显示的网站地址，确认默认英文页面样式正常。
2. 点击右上角 **中文**，确认语言切换正常。
3. 在 Contribute 和 Resources 部分检查任务提案模板、评测记录清单是否可下载。
4. 可在仓库首页右侧 **About** 设置中填入网站地址，方便访客找到。

以后修改文件并提交到 `main`，Pages 会按配置重新发布。

## 项目主页与个人网站的区别

这个仓库发布的是你账号下的 **InclusionMed 项目主页**，默认路径包含 `/InclusionMed/`。

如果以后希望做 `https://knight-flash.github.io/` 这样的个人网站根首页，需要使用名为 **knight-flash.github.io** 的仓库。在个人首页加入项目卡片或链接，就能接到这里，不必移动这个项目。

[GitHub Pages 网站类型与地址说明](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages)

## 内容维护

英文内容稿在 `README.md`，中文内容稿在 `README.zh-CN.md`。静态网站对应 `index.html` 和 `index.zh-CN.html`；后续改文案时应同步更新。`assets/` 包含样式、图标和两份材料。

正式 InclusionMed 网站地址、公开提交渠道和确认后的人员署名暂未补充。当前介绍说明了研发阶段，区分演示数据与公开参考结果。
