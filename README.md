# DJMAX Tool

> **本项目已重构并迁移至 xh Tool。** 旧项目停止功能维护，请前往新项目获取安装包与后续更新。

作者：**鳕烩**。

## 新项目与下载

- **CNB（默认／推荐）**：[xh Tool 0.1.2 下载](https://cnb.cool/linglin520/xh-tool/-/releases/tag/v0.1.2) · [新项目首页](https://cnb.cool/linglin520/xh-tool)
- **GitHub（备用）**：[xh Tool 0.1.2 下载](https://github.com/linglin520/xh-tool/releases/tag/v0.1.2) · [新项目首页](https://github.com/linglin520/xh-tool)

## 迁移说明

我们已经重构了此应用，请点击上方链接获取安装包。

**重构版使用独立包名，需要单独安装，不能覆盖旧 DJMAX Tool。** 旧版本地数据不会自动迁移，请在新版重新配置查分玩家。此次迁移不会卸载旧应用或删除其数据。

旧项目 **0.1.28** 是迁移提示版：安装后启动只显示重构版下载／安装入口，不再返回旧功能。默认从新 CNB 项目获取安装包，可手动切换 GitHub；下载后仍由 Android 系统确认安装。已安装符合身份的重构版可直接打开。

本仓库保留旧发行记录与来源署名，后续功能和版本更新请关注新项目。

## 历史功能

旧版提供 DJMAX 曲库／等级分层、成绩与 B70／B30／S10、个人吃分推荐、整曲收藏、统计曲线、谱面雷达、Steam DLC 优惠及 CLEAR PASS。以下为旧项目使用的数据来源与界面引用记录。

## 数据来源

| 来源 | 使用内容 | 网站与资料 |
| --- | --- | --- |
| V-ARCHIVE | 曲库、曲包、难度、分层、曲绘、玩家成绩、DJ POWER／DJ CLASS／Tier | [网站](https://v-archive.net/) · [API 文档](https://v-archive.net/info/manual/api) |
| EZ2PATTERN | 有明确曲目映射的 BPM、总音符数、时长、Steam 收录日期与韩英曲名，整理为本地资料 | [网站](https://ez2pattern.kr/) · [DJMAX API 文档](https://ez2pattern.kr/djmax/api/docs) |
| Hangibot | 四模式谱面特征标注，保存为本地雷达快照 | [网站](https://hang2bot.vercel.app/) |
| Steam | 音乐 DLC 与通行证商品、官方头图／公告及地区售价，价格可通过 CNB 缓存分发 | [商店](https://store.steampowered.com/dlc/960170/DJMAX_RESPECT_V/) |
| 小黑盒 | 按地区原币的价格历史与备用参考价 | [网站](https://www.xiaoheihe.cn/) |

未知资料显示“—”，不同来源按各自取得时间维护。查询成绩来自 V-ARCHIVE 已收录记录；推荐是个人练习参考。

## 界面引用

[AndroidLiquidGlass／Backdrop](https://github.com/Kyant0/AndroidLiquidGlass) 用于液态玻璃界面，Apache-2.0。段位徽章、星级与达成筛选图案采用用户提供的 [djmax_bests_generate](https://github.com/SoreHait/djmax_bests_generate) 项目 PNG，随包保留 MIT 许可和 SoreHait 的版权声明。数据来源与界面项目分别列出，感谢相关维护者。

本应用为玩家工具，与 DJMAX 官方无隶属关系。
