<p align="center">
  <img src="https://tcp.onemoretry.cc/images/logo/app-icon-1.3.png" alt="TCP调试助手" width="120">
</p>

<h1 align="center">TCP调试助手 · TCP-Debug</h1>

<p align="center">TCP 客户端与服务端调试工具，让连接、收发和报文分析更清晰。</p>

<p align="center">
  <a href="https://tcp.onemoretry.cc/">官方网站</a> ·
  <a href="https://github.com/iamcc30/tcp-debug-tool/releases/tag/v1.3.0">1.3.0 发布说明</a> ·
  <a href="https://apps.apple.com/cn/app/tcp%E8%B0%83%E8%AF%95%E5%8A%A9%E6%89%8B/id6808118556?mt=12">Mac App Store</a>
</p>

## 下载

当前版本：**1.3.0**。

| 平台 | 下载 | 说明 |
| --- | --- | --- |
| macOS · Intel / Apple Silicon | [Mac App Store](https://apps.apple.com/cn/app/tcp%E8%B0%83%E8%AF%95%E5%8A%A9%E6%89%8B/id6808118556?mt=12) | 一次购买，无订阅；由商店安装与更新，价格以当地页面为准 |
| Windows x64 | [下载 EXE](https://github.com/iamcc30/tcp-debug-tool/releases/download/v1.3.0/TCP-Debug-Windows-amd64.exe) | 免费下载，当前发行版未进行代码签名 |
| Linux x64 | [下载可执行文件](https://github.com/iamcc30/tcp-debug-tool/releases/download/v1.3.0/TCP-Debug-Linux-amd64) | 基于 Debian 12 构建，需要兼容的图形桌面运行库 |
| Linux ARM64 | [下载可执行文件](https://github.com/iamcc30/tcp-debug-tool/releases/download/v1.3.0/TCP-Debug-Linux-arm64) | 同上，适用于 ARM64 系统 |

Linux 下载后添加执行权限，例如 `chmod +x TCP-Debug-Linux-amd64`，并安装所需的 OpenGL / X11 运行库。可使用 [SHA256SUMS.txt](https://github.com/iamcc30/tcp-debug-tool/releases/download/v1.3.0/SHA256SUMS.txt) 核验下载完整性。

本次公开发行提供 Windows 与 Linux 制品；Mac 请通过 App Store 获取。

## 主要功能

- **客户端与服务端**：主动建立 TCP 连接，或监听本地端口接收多个客户端；各会话独立管理、收发和断开。
- **多种数据格式**：支持 HEX、ASCII、Binary、JSON，提供长度前缀、分隔符和固定长度分帧。
- **报文分析**：在报文列表与会话流之间切换，查看收发方向、连接状态和字节统计，复制或查看完整报文。
- **重复测试与导出**：复用发送历史、定时发送，将报文导出为 CSV、JSON 或 TXT。
- **中英文即时切换**：保存语言设置后立即生效，无需重启，不中断活动连接。
- **阅读与显示设置**：深色/浅色主题、自动换行、等宽字体和纯数据视图。

1.3.0 新增 TCP 服务端和中英文即时切换，并修复公开构建的版本注入，避免二进制显示旧版本及同版本更新误报。

## 界面预览

以下为 macOS 真实界面的展示图。官网提供更多截图与放大预览。

![客户端与服务端连接管理](https://tcp.onemoretry.cc/images/01-overview-1.3.png)

![中英文界面与深浅主题](https://tcp.onemoretry.cc/images/04-language-1.3.png)

## 快速开始

1. 下载适合当前系统的版本并启动应用。
2. 创建 TCP 客户端连接，或配置服务端监听本地端口。
3. 打开会话，选择发送与接收格式，开始收发和查看报文。
4. 按需启用定时发送、切换语言，或导出报文继续分析。

## 源码与开发文档

**本 GitHub 仓库用于托管发行文件与使用说明，源码以 Gitee 为准。**

GitHub Release 自动生成的 Source code 归档不对应 1.3.0 发行源码。请从 Gitee 获取源码及 `v1.3.0` 标签：

- [Gitee 源码仓库与开发指南](https://gitee.com/785445636/tcp-assistant)
- [完整功能说明](https://gitee.com/785445636/tcp-assistant/blob/master/FEATURES_CN.md)
- [构建与版本注入说明](https://gitee.com/785445636/tcp-assistant/blob/master/QUICK_BUILD.md)
- [Mac App Store 构建说明](https://gitee.com/785445636/tcp-assistant/blob/master/packaging/macos-app-store/README.md)

## 支持

- [官方网站](https://tcp.onemoretry.cc/)
- [隐私政策](https://tcp.onemoretry.cc/privacy.html)
- 联系开发者：[techforcc@gmail.com](mailto:techforcc@gmail.com)
