# 明白日子（HowToLiveBetter）协议站点

HarmonyOS 应用「明白日子」（`com.xmgod.howtolivebetter`）的公开协议页面，通过 GitHub Pages 发布。

## 页面

| 页面 | 路径 |
| --- | --- |
| 协议首页 | `index.html` |
| 隐私政策（中/英） | `privacy-policy.html` |
| 用户协议（中/英） | `user-agreement.html` |

页面支持中英文切换（右上角按钮，或 `?lang=en` 参数），样式与脚本位于 `assets/`。

## 公开链接

- 入口：https://tomkuku588-bot.github.io/HowToLiveBetter/
- 隐私政策：https://tomkuku588-bot.github.io/HowToLiveBetter/privacy-policy.html
- 用户协议：https://tomkuku588-bot.github.io/HowToLiveBetter/user-agreement.html

## 部署

推送到 `main` 分支后，`.github/workflows/pages.yml` 会自动构建并部署到 GitHub Pages（首次运行会自动启用 Pages）。也可在 Actions 页面手动触发（workflow_dispatch）。

## 应用要点（协议内容依据）

- 离线优先：无账号、不联网、不申请任何系统权限、无云同步、无第三方 SDK、无广告/统计/支付。
- 正文内置：应用打包《高性价比人生指南》原书（33 节、614 条），来源开源项目，正文遵循 Unlicense。
- 本地数据：收藏、最近阅读、阅读进度（`reading.db`）、阅读偏好（`reading-settings`），以及习惯、打卡、待办与专注记录，全部保存在设备本地应用沙箱；备份导出导入走系统文件选择器，不经网络。

## 版本记录

- 2026-09-29：首次发布，对应应用版本 1.0.0。
- 2026-10-16：应用改名「明白日子」（审核 9.5 差异化），协议补齐习惯/打卡/待办/专注/统计/备份披露，对应应用版本 1.0.5。
