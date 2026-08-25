# RemotePilot — 用 Apple TV 遥控器控制 Mac

[![Latest Release](https://img.shields.io/github/v/release/kai-wu-cortex/RemotePilot-Releases?display_name=release&label=最新版本)](https://github.com/kai-wu-cortex/RemotePilot-Releases/releases/latest)
![Platform](https://img.shields.io/badge/platform-macOS-000000?logo=apple)
![Apple Silicon](https://img.shields.io/badge/Apple%20Silicon-M1%20及后续芯片-111111)
![License](https://img.shields.io/badge/license-Proprietary-red)

RemotePilot 是一款面向 macOS 的 **Apple TV 遥控器 / Siri Remote 控制工具**。它可以把 Apple TV Remote 变成 Mac 的无线触控板、滚轮、快捷键面板和语音输入设备，支持 Siri Remote **A1962、A2540、A2854** 等型号，适合日常办公、演示、媒体控制、游戏操作和 **Vibe Coding（Vibecoding）** 工作流。

> 本仓库是 RemotePilot 的官方二进制发布与自动更新仓库，仅提供安装包、版本说明和 Sparkle 更新文件，不包含产品源代码。

## 下载 RemotePilot

| 项目 | 说明 |
| --- | --- |
| 最新版本 | **RemotePilot 1.0.1** |
| 支持设备 | Apple TV Remote / Siri Remote A1962、A2540、A2854 |
| 支持电脑 | Apple Silicon Mac（M1、M2、M3、M4 及后续芯片） |
| 系统要求 | macOS 12 或更高版本 |
| 安装包 | [下载最新版 RemotePilot.dmg](https://github.com/kai-wu-cortex/RemotePilot-Releases/releases/latest/download/RemotePilot.dmg) |

## RemotePilot 可以做什么

- **遥控器变触控板**：使用 Siri Remote 的触控区域移动指针、点击和拖动。
- **环形滚动与手势**：用遥控器快速浏览网页、文档、代码和时间线。
- **按键映射**：把 Apple TV 遥控器按键映射为快捷键、系统操作或 App 专属指令。
- **语音输入**：在 Mac 麦克风和专业版遥控器语音之间切换。
- **Typeless 模式**：通过 Siri 按键选择口述、翻译和提问，配合实时波形反馈。
- **Vibe Coding 控制器**：在编程、AI 对话和 Vibecoding 场景中远程触发快捷键、滚动页面与输入语音。
- **按 App 配置**：为浏览器、编辑器、播放器、演示软件和游戏设置不同映射。

## 快速开始

1. 下载最新版 [RemotePilot.dmg](https://github.com/kai-wu-cortex/RemotePilot-Releases/releases/latest/download/RemotePilot.dmg)。
2. 打开 DMG，将 RemotePilot 拖入“应用程序”文件夹。
3. 按住 Siri Remote 的“返回键 + 音量加”约 5 秒进入蓝牙配对模式。
4. 在 macOS 蓝牙设置中连接 Apple TV Remote。
5. 按照应用内使用指南完成辅助功能、输入监控、蓝牙和麦克风权限设置。

当前 GitHub 版本未经过 Apple 公证。如 macOS 阻止首次打开，请前往“系统设置 → 隐私与安全性”，确认应用来源后选择“仍要打开”。

## 官方链接

- 官网：[remotepilot.site](https://remotepilot.site)
- 使用指南：[remotepilot.site/#guide](https://remotepilot.site/#guide)
- 最新版本：[GitHub Releases](https://github.com/kai-wu-cortex/RemotePilot-Releases/releases/latest)

## 适用的 Siri Remote 型号

RemotePilot 面向 Apple TV 遥控器用户，兼容并持续优化以下型号：

- **A1962**：第一代 Siri Remote / Apple TV Remote。
- **A2540**：第二代 Siri Remote / Apple TV Remote。
- **A2854**：第三代 USB‑C Siri Remote / Apple TV Remote。

实际功能会受到遥控器硬件能力、macOS 版本和系统权限影响。

## 关注小红书

在小红书关注 **小吴折腾 AI**，获取 RemotePilot 使用技巧、Apple TV 遥控器玩法、Siri Remote 配置教程和 Vibe Coding 实践。

<p align="center">
  <img src="assets/xiaohongshu-qr.jpg" width="320" alt="小吴折腾AI 小红书二维码，RemotePilot 使用教程与 Vibe Coding 分享">
</p>

小红书号：`63576874406`

## 自动更新

RemotePilot 使用 Sparkle 获取签名更新。应用会读取本仓库 Latest Release 中的 `appcast.xml`，并下载对应的 `RemotePilot.dmg`。请只从官网或本仓库下载发行版本。

## 软件许可

RemotePilot 是**非开源的专有软件（Proprietary Software）**。本仓库公开可见不代表软件以开源方式授权，也不授予复制、修改、反向工程、再分发或商业转售权利。详细条款请阅读 [LICENSE](LICENSE)。

Copyright © 2026 RemotePilot. All rights reserved.
