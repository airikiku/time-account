# Time Account

一个无需服务器的个人时间预算测试版。打开 `index.html` 即可本地试用。

## GitHub Pages 部署
1. 在 GitHub 新建公开仓库 `time-account`。
2. 将 `index.html` 和 `README.md` 上传到仓库根目录并提交。
3. 进入仓库 Settings → Pages → Build and deployment，Source 选择 Deploy from a branch，Branch 选择 `main`，目录选择 `/ (root)`，保存。
4. 等待 GitHub Pages 部署，访问 `https://你的GitHub用户名.github.io/time-account/`。

## 功能
- 每月分类预算、计时、手动记录、编辑及删除时间流水
- 月度预算对比、分类产出指标
- 浏览器 localStorage 保存，JSON 导入与导出

## 已知限制
- 数据仅在当前浏览器，不支持跨设备同步；清理浏览器数据会导致数据丢失，请定期导出。
- 当前月度分类预算为全局设置，修改预算会影响其他月份的展示；后续版本可加入每月预算快照。
- 时间记录按开始日期归属月份；跨月计时尚未自动拆分。
- 正在计时的任务会保存开始时间，关闭页面后可继续计时，但不会发送系统通知。
