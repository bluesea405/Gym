# PocketGym · 健身速记 3.3

适合手机使用的个人健身记录工具：按组记录重量与次数、四组方格、常用动作收藏、力量/有氧记录、训练历史和数据导出。

## GitHub Pages 部署

在此仓库的 **Settings → Pages → Build and deployment** 设置：

- **Source**: Deploy from a branch
- **Branch**: main
- **Folder**: /(root)

保存后，站点地址为 `https://bluesea405.github.io/Gym/`（注意仓库名称大小写）。

iPhone Safari 打开站点后，选择“分享 → 添加到主屏幕”即可安装快捷方式。

> 数据默认储存在当前浏览器的本地存储，不上传到 GitHub，也不会自动跨设备同步。建议定期导出 JSON 备份。

## 3.3 按计划打卡

首页增加上肢 A、下肢 A、上肢 B、下肢 B 四个预置训练日；开始后按动作顺序记录，每一项填写重量和次数后点击「保存并下一步」，会自动载入下一项。可以跳过、返回、恢复进度。原有训练历史数据结构与 LocalStorage key 不变，计划进度单独存储。
