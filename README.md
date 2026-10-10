# 再遇 Axure 原型

此仓库存放 Axure RP 9 导出的 HTML 原型。在线预览入口为 `index.html`，页面导航、图片与交互依赖同级的 `data`、`files`、`images`、`plugins` 和 `resources` 目录。更新时应一起替换完整导出内容，不要只上传单个 HTML 页面。

## 发布到 GitHub Pages

1. 将此目录推送到 GitHub 仓库的 `main` 分支。
2. 在仓库 `Settings` > `Pages` 中选择 `Deploy from a branch`，分支选择 `main`，目录选择 `/ (root)`，保存。
3. Pages 发布完成后，访问 `https://<用户名>.github.io/<仓库名>/`。

仓库和 Pages 站点可能被公开访问。上传前检查原型中是否包含不宜公开的资料。

## 更新原型

从 Axure 重新导出完整 HTML 包，用新文件替换仓库中的旧导出文件；确认入口和资源目录齐全后提交更改。Git 提交记录保留每次更新的历史版本。
