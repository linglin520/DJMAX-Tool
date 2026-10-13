# DJMAX Tool

DJMAX RESPECT V 成绩查询与练习参考工具，原生 Android 应用，支持 Android 8.0 及以上。

作者：**鳕烩**。

## 主要功能

- **曲库查询**：歌曲列表／曲包网格、曲名与作曲家搜索、难度与分层资料、BPM／总音符数／时长、曲绘缓存。
- **成绩查询**：通过 V-ARCHIVE 昵称或用户查询 Token 查询 4B／5B／6B／8B 成绩，保留本地缓存。
- **BEST 100**：分别展示 B70／B30，S10 展示两组各最多 10 条接近入榜的已收录谱面；DJ POWER、DJ CLASS 与徽章汇总。
- **吃分推荐**：基于个人已收录成绩提供主推荐与候补，支持换一个、跳过和进度记录。
- **成长记录**：从成功查询开始积累 DJ POWER 与单谱面准确率曲线，查看成绩统计及近期记录。
- **整曲收藏**：保存整首歌曲，方便回查曲目与详情。
- **外观与交互**：跟随系统／深色／浅色，金色／樱花粉／银白主题；液态玻璃导航、曲绘／整卡过渡、返回顶部和刷新动效。
- **App 搜索入口**：歌曲详情提供 YouTube、bilibili 和网易云的 App 搜索入口。

## 下载与更新

完整安装包放在本仓库 **Releases**，提供 APK 和附带安装说明／摘要的 ZIP。使用相同签名的完整包覆盖安装，无需卸载；曲绘仍按需联网缓存。

软件内检查更新与点击下载将从本次带更新功能的新版本提供，现有 0.1.4 需要手动覆盖安装这一次。下载完成后通过 Android 系统确认安装。

## 数据来源

| 来源 | 使用内容 | 网站与资料 |
| --- | --- | --- |
| V-ARCHIVE | 曲库、曲包、难度、分层、曲绘、玩家成绩、DJ POWER／DJ CLASS／Tier | [网站](https://v-archive.net/) · [API 文档](https://v-archive.net/info/manual/api) |
| EZ2PATTERN | 有明确曲目映射的 BPM、总音符数与时长，整理为本地资料 | [网站](https://ez2pattern.kr/) · [DJMAX API 文档](https://ez2pattern.kr/djmax/api/docs) |

未知资料显示“—”，不同来源按各自取得时间维护。查询成绩来自 V-ARCHIVE 已收录记录；推荐是个人练习参考。

## 界面引用

[AndroidLiquidGlass／Backdrop](https://github.com/Kyant0/AndroidLiquidGlass) 用于液态玻璃界面，Apache-2.0。数据来源与界面项目分别列出，感谢相关维护者。

本应用为玩家工具，与 DJMAX 官方无隶属关系。
