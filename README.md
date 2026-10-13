# SLD-GCB（三闾大夫弓长帛）

> 独立开发，从零做到能用 —— 手机 / 桌面 / 游戏引擎 / AI / 数据库 / 安全，全都自己写。

**技术栈**　`Kotlin` `Jetpack Compose` `C++` `Python` `Media3 / ExoPlayer` `Godot`
`HLS / DASH 流媒体` `自定义网络协议` `本地大模型`

---

## 📱 应用

**梼杌（Android）**
在 App 内置浏览器里走到任意网页，自动找出视频地址并下载成能播的文件；支持加密流解密，还有「浏览器实时探测」抓 JS 动态加载的地址。
`Kotlin · Compose · Media3` → [Taowu-spider-Android](https://github.com/SLD-GCB/Taowu-spider-Android)

**大司农**
局域网传文件 + 聊天：一台开热点、另一台连上就能互传文件和消息，**不用服务器、不走互联网**，安卓 ↔ Windows 任意互通。
`Kotlin + Python · 自研协议` → [DSN-android-windows](https://github.com/SLD-GCB/DSN-android-windows)

**鸿胪寺（桌面 + 安卓）**
开箱即用的本地 AI 应用：**不装 Python、不装 CUDA，拷走就能跑**；既能角色扮演聊天，也能当编程助手（让 AI 读代码、改代码、跑命令）。
`Python / C++ · 本地大模型` → [Windows](https://github.com/SLD-GCB/HLS-AI-Windows) · [Android](https://github.com/SLD-GCB/HLS-AI-Android)

**梼杌（PC 版）** — 上面安卓版的电脑版。`Python · Qt` → [taowu-spider](https://github.com/SLD-GCB/taowu-spider)

**鸿胪寺小程序** — 微信小程序版。【未开源】

---

## 🐉 引擎与底层　`C++`

**烛龙 · 游戏开发引擎** — 自己从零写的一套游戏引擎（渲染 / 资源 / 脚本层），可直接用来开发游戏。
→ [ZhuLong-game-develop-engine](https://github.com/SLD-GCB/ZhuLong-game-develop-engine)

**烛龙 · 开发示例** — 用烛龙引擎做的开发示例项目。
→ [ZhuLong-game](https://github.com/SLD-GCB/ZhuLong-game)

**烛龙 · 通用内核** — 面向多种经典主机的通用模拟器内核。
→ [ZhuLong-game-develop-engine-Kernel](https://github.com/SLD-GCB/ZhuLong-game-develop-engine-Kernel)

---

## 🤖 AI 与模型

**华夏架构** — 自研的 AI 模型架构与训练工程：图像识别（MNIST / 狗品种分类）+ 文本模型原型 + 预训练 / 分词流水线。`Python`【未开源】

---

## 🗄️ 数据与安全

**霸下数据库** — 前后端一体的数据库，**免安装、开箱即用**。`Python` → [baxiadb](https://github.com/SLD-GCB/baxiadb)

**玄武防火墙** — 数据库防火墙：SQL 协议代理 + 威胁检测 + 访问控制 + 审计日志。`Python`【未开源】

---

## 🎮 游戏

**山海界** — 用 Godot 制作的游戏，含城邑 / 建造模块。`Godot`【未开源】

---

## 📬 联系

- 国内：`a15118102941@163.com`
- 国外：`zhangjinrong20051017@gmail.com`
- GitHub：[@SLD-GCB](https://github.com/SLD-GCB)
