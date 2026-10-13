# 什么值得买净化 (SMZDMPurify)

什么值得买 (`com.smzdm.client.android`) 的 LSPosed 净化模块, 使用 libxposed API 102.

## 最新版本

**1.1** (`versionCode=2`), 针对什么值得买 11.1.95 核对并测试.

- 首页底部仅保留「首页 / 好价 / 我的」, 移除发布加号与社区入口.
- 隐藏 KingKong 图标栏、兴趣广场、签到、国家补贴等推广入口, 搜索栏固定置顶.
- 排行榜入口合并到「推荐 | 关注 | 排行榜」同一行右侧, 支持点击与左右滑动切换.
- 过滤开屏广告、运营弹窗、浮窗挂件及穿山甲信息流广告.
- 屏蔽百亿补贴评论区红包分享图、邀请码与水评, 保留真实图文评论并支持秒级呈现与排序.
- 隐藏好价详情页 AI 商品介绍、红包小助手与商品百科.
- 精简我的页与搜索页推广内容.
- 官方红「值」图标, 模块体积深度精简至约 67 KB.

完整更新内容见 [更新日志](CHANGELOG.md).

## 安装与更新

从 [Releases](https://github.com/Xposed-Modules-Repo/io.github.jessire.smzdmpurify/releases) 下载并覆盖安装 APK, 在 LSPosed 中启用模块, 作用域勾选什么值得买. 强制停止并重新打开什么值得买后生效, 无需卸载旧版或清除数据.

## Source

[GitHub 源码](https://github.com/Jessire/SMZDMPurify)
