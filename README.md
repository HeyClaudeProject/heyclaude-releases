# heyClaude 发布

这里只放 heyClaude 桌面客户端的发布文件，**源码不在这里**。

- 每个 Release 里有 `release.json`（经维护者签名的发布清单）和 macOS（Apple 芯片）安装包 `heyClaude-<序号>-darwin-arm64.zip`。
- 已安装的 heyClaude 会自己检查这里的最新发布，核对签名、大小、SHA-256 和代码签名之后才会更新。下载地址公开，但只有维护者私钥签过名的版本才会被安装。

## 第一次安装

1. 打开最新的 Release，下载 `heyClaude-<序号>-darwin-arm64.zip`，解压得到 `heyClaude.app`，拖进“应用程序”。
2. 第一次双击时 macOS 会提示无法验证开发者（这个版本是 ad-hoc 签名，没有经过 Apple 公证）。打开“系统设置 → 隐私与安全性”，在页面下方找到 heyClaude，点“仍要打开”，再确认一次。macOS 15 起“右键 → 打开”不再能放行这类应用。
3. 之后的版本会自动更新：退出时替换，或者在设置里点“立即重启更新”。

## 反馈

在 heyClaude 左下角菜单里点“反馈…”，填好后会在浏览器里打开这里的新建 issue 页面，内容已经预填好，你确认后再提交。也可以直接在 [Issues](https://github.com/HeyClaudeProject/heyclaude-releases/issues) 里新建。

**这里的 issue 是公开的，任何人都能看到。** 不要贴 API key、token、服务器地址、私人路径或对话内容；应用附上的诊断信息只有版本、系统和连接方式，提交前请再看一眼。
