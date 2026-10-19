# SLD-GCB（三闾大夫弓长帛）

> 以 AI 协作的方式做产品 —— 手机 / 桌面 / 游戏引擎 / AI / 数据库 / 安全都做过一遍，并且都做到了能跑能用。

**技术栈**　`Kotlin` `Jetpack Compose` `C++` `Python` `Media3 / ExoPlayer` `Godot`
`HLS / DASH 流媒体` `自定义网络协议` `本地大模型`

**关于开发方式**　以下项目均为**人机协作**完成：产品定位、功能规划与技术方案由我确定；编码借助 AI 编程工具实现；**AI 产出偏离预期时，由我定位问题并推动修正**，最后打包、发布并维护到可正常使用。

**我的 F-Droid 仓库**　<https://github.com/SLD-GCB/SLD-GCB_f-droid> —— 下面的安卓应用可以直接在 F-Droid 里订阅安装。

---

## 📱 应用

**梼杌（Android）**
在 App 内置浏览器里走到任意网页，自动找出视频地址并下载成能播的文件；支持加密流解密，还有「浏览器实时探测」抓 JS 动态加载的地址。
`Kotlin · Compose · Media3` → [Taowu-spider-Android](https://github.com/SLD-GCB/Taowu-spider-Android)

**大司农**
局域网传文件 + 聊天：一台开热点、另一台连上就能互传文件和消息，**不用服务器、不走互联网**，安卓 ↔ Windows 任意互通。
`Kotlin + Python · 自定义传输协议` → [DSN-android-windows](https://github.com/SLD-GCB/DSN-android-windows)

**鸿胪寺（桌面 + 安卓）**
开箱即用的本地 AI 应用：**不装 Python、不装 CUDA，拷走就能跑**；既能角色扮演聊天，也能当编程助手（让 AI 读代码、改代码、跑命令）。
`Python / C++ · 本地大模型` → [Windows](https://github.com/SLD-GCB/HLS-AI-Windows) · [Android](https://github.com/SLD-GCB/HLS-AI-Android)

**梼杌（PC 版）** — 上面安卓版的电脑版。`Python · Qt` → [taowu-spider](https://github.com/SLD-GCB/taowu-spider)

**鸿胪寺小程序** — 微信小程序版。【未开源】

---

## 🐉 引擎与底层　`C++`

**烛龙 · 游戏开发引擎** — 一套包含渲染 / 资源 / 脚本层的游戏引擎，可直接用来开发游戏。
→ [ZhuLong-game-develop-engine](https://github.com/SLD-GCB/ZhuLong-game-develop-engine)

**烛龙 · 开发示例** — 用烛龙引擎做的开发示例项目。
→ [ZhuLong-game](https://github.com/SLD-GCB/ZhuLong-game)

**烛龙 · 通用内核** — 面向多种经典主机的通用模拟器内核。
→ [ZhuLong-game-develop-engine-Kernel](https://github.com/SLD-GCB/ZhuLong-game-develop-engine-Kernel)

---

## 🤖 AI 与模型

**华夏架构** — AI 模型项目：图像识别（MNIST / 狗品种分类）+ 文本模型原型 + 预训练 / 分词流水线。`Python`【未开源】

---

## 🗄️ 数据与安全

**霸下数据库** — 前后端一体的数据库，**免安装、开箱即用**。`Python` → [baxiadb](https://github.com/SLD-GCB/baxiadb)

**玄武防火墙** — 数据库防火墙：SQL 协议代理 + 威胁检测 + 访问控制 + 审计日志。`Python`【未开源】

---

##  网页面板与配套代理工具开发

**HorseBox** — 与我开发的Horse-UI配套的专属代理工具，**免安装、开箱即用**。`dart` → [HorseBox](https://github.com/SLD-GCB/HorseBox)

**Horse-UI** — 我专门开发的代理服务器管理前后端面板，对垃圾线路做了优化，内存占有量低。`go`→ [HorseUI](https://github.com/SLD-GCB/Horse-UI)

---

## 🎮 游戏

**山海界** — 用 Godot 制作的游戏，含城邑 / 建造模块。`Godot`【未开源】

---

## 📬 联系

- 国内：`a15118102941@163.com`
- 国外：`zhangjinrong20051017@gmail.com`
- GitHub：[@SLD-GCB](https://github.com/SLD-GCB)
