# LanguageTeacher Android Download

**[Download 0.3.0-dev APK](https://github.com/NatycorRaven/LanguageTeacher-Releases/releases/download/v0.3.0-dev/LanguageTeacher-0.3.0-dev.apk)**

[Release](https://github.com/NatycorRaven/LanguageTeacher-Releases/releases/tag/v0.3.0-dev) | [SHA-256](https://github.com/NatycorRaven/LanguageTeacher-Releases/releases/download/v0.3.0-dev/sha256.txt) | [Download QR](https://github.com/NatycorRaven/LanguageTeacher-Releases/releases/download/v0.3.0-dev/LanguageTeacher-0.3-download-qr.png)

真人视频口语免费接入试验：从首页进入视频课，接入原生WebRTC、麦克风、字幕、静音、打断与本地学习记录。保留原有英日韩文字课堂、基础小测、计划和词句复盘。

**尚未使用真实LiveAvatar Key验收视频链路。** 本版提供App内配置入口，需安装后填写自己的免费账户Key，确认MIX Flip及所在网络的实际效果；自动化媒体替身测试不代表真人通话已经通过。

## 手机使用

1. Android 8.0+ 下载APK覆盖安装，无须卸载0.2。
2. 首页点击“开始视频口语练习”，通过页面入口注册LiveAvatar免费账户，获取自己的API Key，在App中“保存并检测”。不要在聊天里发送Key。
3. 保持默认Sandbox，授权麦克风后开始；约一分钟、固定Wayne真人形象、不消耗credits。
4. 可静音、打断或结束。最终字幕保存在本地，结束后可查看记录并用已有教学模型生成复盘。

视频试验使用LiveAvatar托管的语音及教学模型；DeepSeek仍用于文字课堂与复盘，其Key不会上传视频服务。

## 免费边界与已知限制

- Sandbox约一分钟；普通Free账户另有10 credits/月、单次两分钟限制，需在App显式确认切换。不是无限免费。已付费或已开启超额的账户可能计费，以服务商设置为准；App不购买套餐或开启超额。
- 英日韩官方能力列表已核验，识别、口音、延迟及大陆网络仍需分别实测。
- 不采集摄像头，没有视觉教学、账号云备份、客观发音评分或内置更新。卸载会清除本地数据。
- APK包含原生媒体库，体积较文字版增大。

## 验证

41项单元测试、28项模拟器设备测试通过；Lint与构建通过。同签名0.2→0.3覆盖升级保留合成记录已验证。课堂与媒体测试使用合成替身，无真实凭据。源码实现提交：f37be7dd9d7a051062b150d8a90878b83e0af7f5。

附件APK、sha256.txt及下载二维码。请从本仓库下载，开发签名与0.1/0.2保持一致。


`latest.json` records distribution metadata; the app does not check for updates automatically. Source remains private. This public repository contains download notes and metadata only.
