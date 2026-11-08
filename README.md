# 今日待办清单 · GitHub Pages 静态版

## 👉 打开网站（不是这个仓库页面）

# [https://zc3307511755.github.io/today-todo/](https://zc3307511755.github.io/today-todo/)

地址栏必须以 **`zc3307511755.github.io`** 开头才是网站；如果地址是 `github.com/zc3307511755/today-todo`，那是仓库源码页，不是应用页面。

---

功能：新增（空白任务不添加）、勾选完成、删除、剩余计数与完成率、全部 / 待完成 / 已完成筛选、手机端适配。数据保存在当前浏览器的 localStorage，不跨设备同步。

> 说明：受云服务 Origin 校验限制，GitHub Pages 域名下无法使用账号登录与云端同步。带登录和跨设备同步的正式版在 https://today-todo-24403.app.workbuddy.host/?sharecode=EJ2JVSND5V

## 部署结构

- `docs/index.html`：站点页面（GitHub Pages 源为 `main` 分支 `/docs`）
- `docs/.nojekyll`：跳过 Jekyll 处理

改样式直接编辑 `docs/index.html` 并推送到 `main`，Pages 会自动重新构建。
