# 红果短剧Mac客户端SAF版

独立 macOS 客户端，沿用用户提供的应用图标。提供 Apple 芯片 arm64 和 Intel x64 安装包。

## 下载 0.8.1

适用于 macOS 13.0 或更新版本。应用名称为「红果短剧Mac客户端SAF版」。

- [Apple 芯片（M 系列）DMG](https://github.com/zqzhuhai-commits/hongguo-saf-mac/releases/download/v0.8.1/Hongguo-Mac-SAF-0.8.1-arm64.dmg)
- [Intel 芯片 DMG](https://github.com/zqzhuhai-commits/hongguo-saf-mac/releases/download/v0.8.1/Hongguo-Mac-SAF-0.8.1-x64.dmg)
- [发布页面：ZIP、SHA-256 校验文件和启动验证报告](https://github.com/zqzhuhai-commits/hongguo-saf-mac/releases/tag/v0.8.1)

两个架构分别在 macOS 环境通过 18 项自动测试和应用启动检查，并验证名称、版本、图标、架构及 ad-hoc 签名。

完整源码位于 `desktop/`，安装与构建说明见 [desktop/README-Mac.md](desktop/README-Mac.md)。

无需安卓模拟器。功能包括剧集浏览、搜索、选集、倍速、全屏、收藏及 JSON 备份导入导出。

使用本地 ad-hoc 签名，未配置 Apple Developer ID 和 Apple 公证。自动检查不代表真实剧集播放验收。

源码以 GPL-3.0-only 发布，参考 [N3urda/hongguoTV](https://github.com/N3urda/hongguoTV)。
