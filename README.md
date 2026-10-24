# LanguageTeacher 安卓下载

面向中国上班族的英日韩外语学习 App。源码和设计在私有仓库管理，这里提供开发体验 APK 与版本索引。

## 当前版本：0.2.0 文字学习交互体验版

**[点击下载安卓 APK](https://github.com/NatycorRaven/LanguageTeacher-Releases/releases/download/v0.2.0-dev/LanguageTeacher-0.2.0-dev.apk)**

[版本说明与附件](https://github.com/NatycorRaven/LanguageTeacher-Releases/releases/tag/v0.2.0-dev) · [全部版本](https://github.com/NatycorRaven/LanguageTeacher-Releases/releases) · [SHA-256 校验](https://github.com/NatycorRaven/LanguageTeacher-Releases/releases/download/v0.2.0-dev/sha256.txt)

Android 8.0 及以上。手机下载 APK 后打开，按系统提示允许浏览器或文件管理器安装。0.1 用户可直接覆盖安装，无须卸载；同签名升级保留会话已在模拟器验证。

## 可以体验

- 首次学习偏好、今日／练习／记忆／我的四页导航。
- 英日韩 18 个职场和旅行场景，表达提示、开场示范、每语五题基础小测和按时间调整的规则计划。
- 配置 DeepSeek 或兼容 HTTPS 服务，与文字家教对话、重试失败请求、继续历史课堂。
- 生成引用对话原文的地道表达和单词复盘，翻面回忆并自评熟悉。

安装后进入“我的”填写自己的 API Key，保存配置并测试连接，再从“练习”开始课堂。默认 API 基础地址 https://api.deepseek.com ，模型名称 deepseek-flash 可修改，以账户实际支持为准。测试及课堂请求会产生自己服务商账户用量；对话上下文发送至配置的地址，Key 加密保存在本机。

无需 Key 可使用小测、计划与场景提示。本轮自动化使用合成模型替身，未以真实 Key 验收 DeepSeek 服务，请配置后自行确认连接、额度与教学效果。小测仅五题，不等同完整口语或发音评级。

## 当前边界

开发预览尚无账号云备份、语音、真人数字人、视频聊天、摄像头教学或内置自动更新。记录只在本机，卸载会清除；卡片熟悉度是自评，尚无间隔复习调度。

后续渠道保持相同开发签名及包名，版本代码递增。其他机器或 CI 临时签名构建不保证能覆盖此渠道。

`latest.json` 仅是发布元数据；开发预发布请使用具体版本页或全部版本页，不依赖 GitHub 的 `/releases/latest`。
