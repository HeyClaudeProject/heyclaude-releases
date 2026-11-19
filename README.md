# heyClaude 发布

这里只放 heyClaude 桌面客户端的发布文件，**源码不在这里**。

- 每个 Release 里有 `release.json`（经维护者签名的发布清单）和 macOS（Apple 芯片）安装包 `heyClaude-<序号>-darwin-arm64.zip`。
- 已安装的 heyClaude 会自己检查这里的最新发布，核对签名、大小、SHA-256 和代码签名之后才会更新。下载地址公开，但只有维护者私钥签过名的版本才会被安装。

## 第一次安装

1. 打开最新的 Release，下载 `heyClaude-<序号>-darwin-arm64.zip`，解压得到 `heyClaude.app`，拖进“应用程序”。
2. 第一次打开时在“应用程序”里**右键 → 打开**（这个版本没有经过 Apple 公证）。
3. 之后的版本会自动更新：退出时替换，或者在设置里点“立即重启更新”。
