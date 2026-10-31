# ChatReader

读取本机微信群聊，使用本地模型整理摘要、原文引用和待办。聊天分析在本机完成，模型权重首次使用时按需下载。

## 下载 1.1.1

| 平台 | 安装包 |
| --- | --- |
| Windows x64 | [ChatReader-1.1.1-Setup.exe](https://github.com/ZehengLi-05/ChatReader/releases/download/v1.1.1/ChatReader-1.1.1-Setup.exe) |
| Apple Silicon Mac | [ChatReader-1.1.1-macos-arm64.dmg](https://github.com/ZehengLi-05/ChatReader/releases/download/v1.1.1/ChatReader-1.1.1-macos-arm64.dmg) |

[发布说明与校验文件](https://github.com/ZehengLi-05/ChatReader/releases/tag/v1.1.1)

Mac 需要 macOS 14 或更高版本，仅支持 M 系列芯片。打开 DMG 后把应用拖入“应用程序”。预览包尚未获得 Apple 公证；首次打开可能需要在“系统设置 → 隐私与安全性”确认。

## 更新

- Mac 新构建支持自动检查、下载和确认后重启更新，失败时恢复旧应用及对应数据库。此前下载的旧 Mac 1.1.1 需手动安装本页的新构建一次，之后才能使用该功能。
- Windows 1.1.1 暂提供手动覆盖安装。原发布签名密钥配置完成前，现有 Windows 自动更新渠道保持 1.0.0；1.1.1 的自动升级包暂未发布。
- 更新应用保留本机资料和模型，模型权重不随应用更新重新下载。

## 首次连接 Mac 微信

需要授予 ChatReader 完全磁盘访问权限，并安装 Xcode Command Line Tools。连接窗口会说明系统管理员授权、微信原应用备份、临时签名及按提示重新登录的步骤；连接完成后可恢复官方微信。已在微信 4.1.15 上验证本机群聊记录读取，其他版本以应用内检查结果为准。

真实聊天的 Qwen 9B 摘要测试曾因系统内存不足而未完成；本地模型可用性取决于设备资源。具体验证范围和限制见发布说明。

此仓库用于软件下载与发布；源码由维护者在独立仓库管理。
