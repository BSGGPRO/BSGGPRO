## BSGGPRO

做硬件和软件之间那层东西。最近在拿一块 ESP32-P4 折腾。

### 在做的

**[esp32p4-hid-agent](https://github.com/BSGGPRO/esp32p4-hid-agent)**
用 ESP32-P4 板子当 Windows 的键盘鼠标。一条 JSON 作业走完「截图 → 判断 → 按键 → 核对」。
走的是真 USB HID，不用装驱动，也不往目标进程里注入东西。

**[itchio](https://github.com/BSGGPRO/itchio)**
itch.io 网页游戏的下载器和启动器，另带一个局域网服务器，手机平板输地址就能玩。
只有工具，没有游戏文件。

**[itchio-ios-webview-shell](https://github.com/BSGGPRO/itchio-ios-webview-shell)**
把 Unity WebGL 游戏套进 iOS App 的壳：本地起 HTTP 服务给 WKWebView 加载，
GitHub Actions 出未签名 IPA。只有壳，没有游戏内容。

### 其他

- 全部 MIT
- 有问题开 issue

---

Hardware, and the layer between it and software. Currently an ESP32-P4 board.

- **esp32p4-hid-agent** — the board as a real USB keyboard and mouse for Windows.
- **itchio** — itch.io downloader, launcher and LAN server. Tools only, no game content.
- **itchio-ios-webview-shell** — Unity WebGL wrapped in an iOS app shell.
