# 拯救ADHD · 浏览器交互预览

可交互的独立网页原型，包含事项、物品展开、计时、日历和购物清单，用于讨论界面与操作。

- 使用示例数据，操作记录保存在各自浏览器的 localStorage 中。
- 与手机 App 数据独立；网页操作不会修改手机记录。
- 网页文件更新部署后，会自动检查更新；已保存记录保留，打开的表单会延后刷新。
- Android 的后台计时、通知和权限行为仍需在实际 App 中验证。

## GitHub Pages

仓库 Settings → Pages → Build and deployment：选择 Deploy from a branch，分支 `main`，目录 `/ (root)`。

## 本地运行

```bash
python3 -m http.server 4173
```

在同一台电脑浏览器打开 `http://127.0.0.1:4173`。

`index.html` 为包含 CSS 和 JavaScript 的单文件网页，由独立预览源码生成。
