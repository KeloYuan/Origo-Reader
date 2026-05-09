     1|<p align="center">
     2|  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a1b26,100:0d1117&height=200&section=header&text=Origo%20Reader&fontSize=50&fontColor=f7768e&fontAlignY=40&desc=%E5%B0%8F%E5%85%83%E8%AF%BB%E4%B9%A6&descSize=18&descAlignY=60&descAlign=50&animation=fadeIn" width="100%" />
     3|</p>
     4|
     5|<p align="center">
     6|  <b>小元读书</b> — 专注阅读本身的电子书阅读器<br/>
     7|  <i>Origo Reader — An ebook reader that lets you just read.</i>
     8|</p>
     9|
    10|---
    11|
    12|## 📖 两个版本，同一个愿景
    13|
    14|小元读书有 **两个版本**，分别面向不同的使用场景：
    15|
    16|<table>
    17|  <tr>
    18|    <th></th>
    19|    <th align="center">🟢 Open Reading<br/><sub>开源跨平台版</sub></th>
    20|    <th align="center">🟣 Origo<br/><sub>原生 iOS 版</sub></th>
    21|  </tr>
    22|  <tr>
    23|    <td><b>平台</b></td>
    24|    <td align="center">Android · iOS · macOS · Windows · Linux</td>
    25|    <td align="center">iOS · macOS</td>
    26|  </tr>
    27|  <tr>
    28|    <td><b>技术栈</b></td>
    29|    <td align="center">Flutter + Dart + Rust</td>
    30|    <td align="center">Swift + SwiftUI + CoreText</td>
    31|  </tr>
    32|  <tr>
    33|    <td><b>开源</b></td>
    34|    <td align="center">✅ MIT 开源</td>
    35|    <td align="center">🔒 闭源</td>
    36|  </tr>
    37|  <tr>
    38|    <td><b>格式</b></td>
    39|    <td align="center">EPUB · PDF · TXT · ZIP</td>
    40|    <td align="center">EPUB · PDF · TXT</td>
    41|  </tr>
    42|  <tr>
    43|    <td><b>仓库</b></td>
    44|    <td align="center"><a href="https://github.com/KeloYuan/open-reading">→ open-reading</a></td>
    45|    <td align="center">本仓库介绍</td>
    46|  </tr>
    47|</table>
    48|
    49|---
    50|
    51|## 🟢 Open Reading — 开源跨平台版
    52|
    53|> 基于 Flutter 构建，一套代码覆盖五个平台。
    54|
    55|**仓库：[github.com/KeloYuan/open-reading](https://github.com/KeloYuan/open-reading)**
    56|
    57|### 特性
    58|
    59|- 📄 多格式支持 — EPUB · PDF · TXT · ZIP
    60|- 📐 智能分页引擎，二分搜索算法精准排版
    61|- 🔄 多种翻页模式 — 翻页 / 滑动 / 滚动 / 3D 仿真翻页
    62|- 🎨 8 种阅读主题 + 自定义主题
    63|- 🔤 字号 · 行距 · 字距 · 缩进，精细排版调节
    64|- 🔖 书签 · 高亮 · 笔记
    65|- 🔊 TTS 文本朗读 + 逐句高亮
    66|- 📊 阅读统计可视化
    67|- ☁️ WebDAV 全量同步
    68|- 🦀 Rust 核心引擎，极致性能
    69|
    70|### 快速开始
    71|
    72|```bash
    73|git clone https://github.com/KeloYuan/open-reading.git
    74|cd open-reading
    75|flutter pub get
    76|flutter run
    77|```
    78|
    79|👉 **详细文档、安装包下载、路线图请前往 [open-reading](https://github.com/KeloYuan/open-reading) 仓库。**
    80|
    81|---
    82|
    83|## 🟣 Origo — 原生 iOS 版
    84|
    85|> 用 Swift 从零构建，为 Apple 生态深度优化的阅读体验。
    86|
    87|Origo 是小元读书的 **原生 iOS / macOS 版本**，采用 Swift + SwiftUI + CoreText 全原生技术栈，追求在 Apple 设备上最极致的阅读体验。
    88|
    89|### 与 Flutter 版的区别
    90|
    91|| 维度 | Origo (原生) | Open Reading (Flutter) |
    92||------|-------------|----------------------|
    93|| 排版引擎 | CoreText / TextKit 原生排版 | WebView (Foliate) + Rust Core |
    94|| TXT 分页 | 原生逐字排版，真实页码 | 二分搜索 + Flutter 渲染 |
    95|| 定位系统 | CanonicalLocator，设备无关 | 同，Anchor-based |
    96|| 性能 | 原生级，零桥接开销 | 跨平台桥接 |
    97|| 平台集成 | 原生 Share Sheet、Spotlight、Shortcuts | Flutter 通用层 |
    98|| AI 阅读助手 | 原生集成 | 内置 AI UI |
    99|
   100|### 核心能力
   101|
   102|- **原生 TXT 阅读** — Swift CoreText 逐字排版，真实设备页码，不依赖 WebView
   103|- **CanonicalLocator** — 阅读进度、书签、高亮的唯一真相源，换字号换设备均可恢复
   104|- **章节索引 + 窗口化分页** — 首屏秒开，后台预排前后章节，滑动零掉帧
   105|- **EPUB / PDF 阅读** — 基于 Readium Swift Toolkit
   106|- **AI 阅读助手** — 原生集成，随时问答
   107|- **Supabase 云同步** — 书库、进度、笔记跨设备同步
   108|- **书源系统** — 在线搜索与导入书籍
   109|- **阅读统计** — 每日 / 每周 / 每月阅读数据
   110|- **原生 TTS** — 逐句朗读 + 进度同步
   111|
   112|### 技术架构
   113|
   114|```
   115|Origo Reader/
   116|├── App/            # 应用入口、依赖组合根
   117|├── Features/       # 页面层 — AI · 书库 · 阅读器 · 笔记 · 设置 · 统计
   118|├── Core/           # 核心能力 — Reader · Sync · API · Auth · Networking
   119|├── Data/           # 数据层 — 持久化、DAO、数据模型
   120|├── DesignSystem/   # 设计系统
   121|├── Models/         # 领域模型
   122|├── Services/       # 业务服务
   123|└── Resources/      # 资源文件
   124|```
   125|
   126|### 状态
   127|
   128|Origo 目前仍在积极开发中，暂未公开发布。如需体验，请关注本仓库的 Release 动态。
   129|
   130|---
   131|
   132|## 🌍 关于小元读书
   133|
   134|小元读书的愿景很简单：**让阅读回归阅读本身。**
   135|
   136|- 不做社交，不做书城弹窗，不做开屏广告
   137|- 只关心排版好不好看、翻页顺不顺手、笔记好不好找
   138|- 两个版本互补：Open Reading 覆盖全平台，Origo 在 Apple 设备上做到极致
   139|
   140|---
   141|
   142|<p align="center">
   143|  <b>小元读书</b> — <i>Reading, refined.</i><br/><br/>
   144|  <a href="https://github.com/KeloYuan/open-reading">⭐ Open Reading (开源版)</a>
   145|</p>
   146|