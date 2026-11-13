# iPhone 17 Pro · 拆解工作台

包含完整的静态网站：8 步拆解、18 个可选择部件、三种机身配色和截图导出。

`site.zip` 保存了网站的 HTML、JavaScript、样式、字体、摄影素材、3D 模型及署名资料。发布过程从这个归档解压文件，无需调用 ChatGPT Sites 或任何 AI 接口。

## 发布

在仓库的 Settings → Pages 中，将 Source 设为 GitHub Actions。提交 `site.zip` 和 `.github/workflows/deploy.yml` 后，工作流会将网站发布到 GitHub Pages。此配置使用 `main` 分支，也支持在 Actions 页面手动运行。

后续更新时替换 `site.zip`，正式网址保持不变。网站运行期间不需要本地电脑保持开机。

## 素材署名

本项目用于非商业演示。外观模型、内部摄影、环境光和字体的来源及许可保存在归档内的 `assets/credits.html`、`assets/MODEL-LICENSE.md`、`assets/PHOTOGRAPHY-LICENSE.md` 与 `vendor/` 中。请保留这些署名和许可。

内部采用摄影辅助的三维重建，微小结构有简化，并非厂商 CAD 或实物扫描模型。
