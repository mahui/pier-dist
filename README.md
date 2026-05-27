# Pier

驻留在 macOS 菜单栏的轻量资源查看工具 —— **端口 / 进程 / 系统 / 开发者工具**一屏速览、一键处理。原生 SwiftUI，空闲约 0% CPU，纯本地、无追踪。

> 本仓库分发 Pier 的发布版本，各版本 DMG 见 [Releases](../../releases)。

## 安装

```bash
brew install --cask mahui/tap/pier
```

或从 [Releases](../../releases/latest) 下载 `Pier.dmg` 拖进「应用程序」。要求 macOS 14（Sonoma）及以上，Apple 芯片与 Intel 均可，已 Developer ID 签名 + Apple 公证。

## 功能

- **端口** — 每个 TCP / UDP 监听端口、占用进程与 App 图标、IPv4·IPv6 标签、对外暴露提醒；一键结束占用。
- **进程** — 按 CPU / 内存实时排序的 Top 进程，展开看完整命令行、路径、父进程，结束或强制结束。
- **系统** — CPU、内存、交换、磁盘、实时网速一屏速览，可把某个实时数字钉在菜单栏图标旁。
- **开发者** — 在菜单栏直接启动 / 停止 / 重启 Docker / Podman 容器与 Homebrew 服务，不用打开终端。

## 特点

- ⚡ **轻量** — 原生 SwiftUI，只在查看时采样，空闲 CPU 趋近于零。
- 🔒 **隐私** — 端口、进程、系统数据全在本机读取，从不上传，无第三方追踪。
- ⌘ **触手可及** — 常驻菜单栏，一键开合，不占 Dock。
- 🌐 **双语 · 深色** — 中文 / English 即时切换，浅色 / 深色 / 跟随系统。

更多介绍见官网 <https://pier.app.mahui.me/>。
