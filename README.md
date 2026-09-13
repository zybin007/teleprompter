# 提词器 · 会议发言助手

一个纯前端、可离线使用的会议发言提词器，手机扫码即可装到桌面当 App 用。

在线体验：https://15bb664b4a5a4174a88c3c6200c6fef0.app.workbuddy.host

## 功能特性

- 逐行高亮：当前行高亮跟随滚动，不跟丢
- 匀速滚动：三档速度（默认 / 1.2 倍 / 1.5 倍），点屏幕暂停、再点继续
- 自由滑行：手指上下滑动浏览，不闪屏、不卡顿
- Markdown 支持：标题、加粗、斜体、列表、引用、分割线
- 四档字号 + 可调行距 / 页边距
- 六色高亮配色 + 明暗主题
- 发言计时器
- 离线可用：讲稿存本机，断网也能开

## 使用方法

1. 手机打开在线链接
2. 浏览器菜单选择「添加到主屏幕 / 安装应用」（iOS：Safari 分享 → 添加到主屏幕）
3. 桌面出现图标，点开即全屏、离线运行

## 技术栈

纯前端 PWA：HTML + CSS + JavaScript，无依赖、无框架。

- Service Worker 离线缓存
- Web App Manifest（桌面图标 + 全屏）
- localStorage 本地存储讲稿

## 目录结构

| 文件 | 作用 |
|---|---|
| index.html | 主程序 |
| manifest.json | PWA 清单 |
| sw.js | Service Worker 离线缓存 |
| icon.png | 应用图标 |
| qrcode.png | 分享二维码 |

## 许可

本项目采用 [MIT License](LICENSE)，可自由使用、修改、商用，保留署名即可。

---

# Teleprompter · Meeting Speech Assistant

A pure front-end, offline-capable teleprompter. Scan the QR code and add it to your home screen to use it like a native app.

Live demo: https://15bb664b4a5a4174a88c3c6200c6fef0.app.workbuddy.host

## Features

- Line-by-line highlight that follows the scroll
- Smooth auto-scroll with three speeds (default / 1.2x / 1.5x); tap to pause, tap again to resume
- Free manual scrolling without flicker
- Markdown support: headings, bold, italic, lists, quotes, dividers
- Four font sizes with adjustable line height and margins
- Six highlight colors plus light/dark themes
- Speech timer
- Offline-ready: scripts are stored locally, works without a network

## Usage

1. Open the live link on your phone
2. Tap "Add to Home Screen / Install App" from the browser menu (iOS: Safari → Share → Add to Home Screen)
3. An app icon appears on your home screen; tap to launch in full screen, offline

## Tech Stack

Pure front-end PWA: HTML + CSS + JavaScript. No dependencies, no framework.

- Service Worker for offline caching
- Web App Manifest (home-screen icon + full screen)
- localStorage for storing scripts

## Project Structure

| File | Purpose |
|---|---|
| index.html | Main app |
| manifest.json | PWA manifest |
| sw.js | Service Worker (offline cache) |
| icon.png | App icon |
| qrcode.png | Share QR code |

## License

Licensed under the [MIT License](LICENSE). Free to use, modify, and use commercially, with attribution.
