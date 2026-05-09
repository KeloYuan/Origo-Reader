     1|<p align="center">
     2|  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,50:1a1020,100:0a0a0a&height=220&section=header&text=小元读书&fontSize=60&fontColor=e8c4f0&fontAlignY=38&desc=Origo%20Reader%20%E2%80%94%20Reading%2C%20refined.&descSize=18&descAlignY=62&descAlign=50&animation=fadeIn" width="100%" />
     3|</p>
     4|
     5|<p align="center">
     6|  <b>专注阅读本身的电子书阅读器</b><br/>
     7|  <sub>不社交 · 不弹窗 · 不开屏广告 · 只安静地读书</sub>
     8|</p>
     9|
    10|<p align="center">
    11|  <img src="https://img.shields.io/badge/Project-Monorepo-purple?style=flat-square" />
    12|  <img src="https://img.shields.io/badge/Versions-2-blue?style=flat-square" />
    13|  <img src="https://img.shields.io/badge/Platforms-5-brightgreen?style=flat-square" />
    14|  <a href="https://github.com/KeloYuan/Origo-Reader/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow?style=flat-square" /></a>
    15|</p>
    16|
    17|<br/>
    18|
    19|<p align="center">
    20|  <b>小元读书</b> 有两个版本，共享同一个愿景，面向不同的使用场景。
    21|</p>
    22|
    23|<table>
    24|  <tr>
    25|    <th width="4%"></th>
    26|    <th width="48%" align="center">
    27|      <img src="https://img.shields.io/badge/-Open_Reading-00C853?style=for-the-badge&logo=open-source-initiative&logoColor=white" /><br/>
    28|      <sub>开源跨平台版</sub>
    29|    </th>
    30|    <th width="48%" align="center">
    31|      <img src="https://img.shields.io/badge/-Origo-7C4DFF?style=for-the-badge&logo=apple&logoColor=white" /><br/>
    32|      <sub>原生 iOS / macOS 版</sub>
    33|    </th>
    34|  </tr>
    35|  <tr>
    36|    <td><b>技术栈</b></td>
    37|    <td align="center">
    38|      <img src="https://img.shields.io/badge/Flutter-3.35-blue?style=flat&logo=flutter" />
    39|      <img src="https://img.shields.io/badge/Dart-3.9-0175C2?style=flat&logo=dart" />
    40|      <img src="https://img.shields.io/badge/Rust-da4326?style=flat&logo=rust" />
    41|    </td>
    42|    <td align="center">
    43|      <img src="https://img.shields.io/badge/Swift-5-orange?style=flat&logo=swift" />
    44|      <img src="https://img.shields.io/badge/SwiftUI-blue?style=flat" />
    45|      <img src="https://img.shields.io/badge/CoreText-333?style=flat" />
    46|    </td>
    47|  </tr>
    48|  <tr>
    49|    <td><b>平台</b></td>
    50|    <td align="center">
    51|      Android · iOS · macOS · Windows · Linux
    52|    </td>
    53|    <td align="center">
    54|      iOS · macOS
    55|    </td>
    56|  </tr>
    57|  <tr>
    58|    <td><b>开源</b></td>
    59|    <td align="center">✅ MIT</td>
    60|    <td align="center">🔒 闭源</td>
    61|  </tr>
    62|  <tr>
    63|    <td><b>格式</b></td>
    64|    <td align="center">EPUB · PDF · TXT · ZIP</td>
    65|    <td align="center">EPUB · PDF · TXT</td>
    66|  </tr>
    67|  <tr>
    68|    <td><b>仓库</b></td>
    69|    <td align="center"><a href="https://github.com/KeloYuan/open-reading">→ <b>open-reading</b></a></td>
    70|    <td align="center">本仓库</td>
    71|  </tr>
    72|</table>
    73|
    74|<br/>
    75|
    76|---
    77|
    78|<br/>
    79|
    80|## 🟢 Open Reading — 开源跨平台版
    81|
    82|<p align="center">
    83|  <a href="https://github.com/KeloYuan/open-reading">
    84|    <img src="https://img.shields.io/badge/🔗_源码仓库-open--reading-00C853?style=for-the-badge&logo=github&logoColor=white" />
    85|  </a>
    86|</p>
    87|
    88|> 基于 Flutter 构建，一套代码覆盖五个平台。
    89|> 核心解析引擎使用 Rust 编写，兼顾性能与跨平台一致性。
    90|
    91|<br/>
    92|
    93|<table>
    94|  <tr>
    95|    <td width="50%" valign="top">
    96|
    97|#### 📖 阅读体验
    98|- 📄 多格式 — EPUB · PDF · TXT · ZIP
    99|- 📐 二分搜索精准分页
   100|- 🔄 翻页 / 滑动 / 滚动 / 3D 仿真
   101|- 🎨 多种阅读主题 + 自定义
   102|- 🔤 字号 · 行距 · 字距 · 缩进
   103|- 🌙 护眼暗色模式
   104|
   105|</td>
   106|    <td width="50%" valign="top">
   107|
   108|#### 🛠️ 智能工具
   109|- 🔖 书签 · 一键快速跳转
   110|- ✏️ 高亮标注 + 笔记
   111|- 🔊 TTS 朗读 + 逐句高亮
   112|- 📊 阅读统计可视化
   113|- ☁️ WebDAV 全量同步
   114|- 🦀 Rust 核心引擎
   115|
   116|</td>
   117|  </tr>
   118|</table>
   119|
   120|```bash
   121|git clone https://github.com/KeloYuan/open-reading.git && cd open-reading
   122|flutter pub get && flutter run
   123|```
   124|
   125|<p align="center">
   126|  <sub>👉 详细文档、安装包、路线图请前往 <a href="https://github.com/KeloYuan/open-reading"><b>open-reading</b></a></sub>
   127|</p>
   128|
   129|<br/>
   130|
   131|---
   132|
   133|<br/>
   134|
   135|## 🟣 Origo — 原生 iOS / macOS 版
   136|
   137|> 用 Swift 从零构建，为 Apple 生态深度优化的阅读体验。
   138|
   139|<br/>
   140|
   141|### 为什么还需要一个原生版本？
   142|
   143|Flutter 版已经足够好用，但原生版能做到：
   144|
   145|- **真实排版** — CoreText 逐字排版，TXT 分页结果来自真实设备渲染，不是估算
   146|- **零桥接开销** — 纯 SwiftUI，每个交互都丝滑到像素级
   147|- **深度系统集成** — Share Sheet · Spotlight 搜索 · Shortcuts 快捷指令 · Widget
   148|- **极致首屏** — 章节索引缓存 + 窗口化分页，打开就看，不等待
   149|
   150|<br/>
   151|
   152|### 核心能力
   153|
   154|<table>
   155|  <tr>
   156|    <td width="33%" valign="top" align="center">
   157|
   158|#### 📖 原生阅读
   159|Swift CoreText 逐字排版
   160|真实设备页码
   161|不依赖 WebView
   162|滑动零掉帧
   163|
   164|</td>
   165|    <td width="33%" valign="top" align="center">
   166|
   167|#### 🎯 CanonicalLocator
   168|进度 · 书签 · 高亮的唯一真相源
   169|换字号、换设备均可恢复
   170|设备无关的文本锚定
   171|
   172|</td>
   173|    <td width="33%" valign="top" align="center">
   174|
   175|#### 🤖 AI 阅读助手
   176|原生集成，随时问答
   177|选中文字即可解释
   178|全文知识对话
   179|
   180|</td>
   181|  </tr>
   182|  <tr>
   183|    <td valign="top" align="center">
   184|
   185|#### ☁️ Supabase 同步
   186|书库 · 进度 · 笔记
   187|跨设备无缝衔接
   188|
   189|</td>
   190|    <td valign="top" align="center">
   191|
   192|#### 📊 阅读统计
   193|每日 / 每周 / 每月
   194|阅读时长与趋势
   195|
   196|</td>
   197|    <td valign="top" align="center">
   198|
   199|#### 🔊 原生 TTS
   200|逐句朗读
   201|进度实时同步
   202|语速 · 音调可调
   203|
   204|</td>
   205|  </tr>
   206|</table>
   207|
   208|<br/>
   209|
   210|### 架构
   211|
   212|```
   213|Origo Reader/
   214|├── App/            # 入口 · 依赖组合根
   215|├── Features/       # 页面 — AI · 书库 · 阅读器 · 笔记 · 设置 · 统计
   216|├── Core/           # 能力 — Reader · Sync · API · Auth · Networking
   217|├── Data/           # 数据 — 持久化 · DAO · 模型
   218|├── DesignSystem/   # 设计系统
   219|├── Models/         # 领域模型
   220|├── Services/       # 业务服务
   221|└── Resources/      # 资源文件
   222|```
   223|
   224|<br/>
   225|
   226|### 技术选型
   227|
   228|| 层级 | 选择 | 理由 |
   229||------|------|------|
   230|| UI | SwiftUI | 声明式，Apple 原生，动画流畅 |
   231|| TXT 排版 | CoreText | 逐字控制，真实页码，零依赖 |
   232|| EPUB / PDF | Readium Swift Toolkit | 成熟开源方案 |
   233|| 云同步 | Supabase | 实时同步 + Auth + Storage |
   234|| 定位系统 | CanonicalLocator | 自研，设备无关文本锚定 |
   235|| 分页 | 窗口化 + 后台预排 | 首屏秒开，滑动不掉帧 |
   236|
   237|<br/>
   238|
   239|### 状态
   240|
   241|> 🚧 积极开发中，暂未公开发布。
   242|> 如需体验，请关注本仓库的 [Releases](https://github.com/KeloYuan/Origo-Reader/releases) 动态。
   243|
   244|<br/>
   245|
   246|---
   247|
   248|<br/>
   249|
   250|## 🌍 关于小元读书
   251|
   252|<p align="center">
   253|  <b>让阅读回归阅读本身。</b>
   254|</p>
   255|
   256|<p align="center">
   257|  排版好不好看 · 翻页顺不顺手 · 笔记好不好找<br/>
   258|  <sub>—— 这些才是阅读器该关心的事。</sub>
   259|</p>
   260|
   261|<br/>
   262|
   263|<p align="center">
   264|  <img src="https://img.shields.io/badge/⭐_Star_支持-open--reading-FFD600?style=for-the-badge&logo=github&logoColor=black" />
   265|</p>
   266|
   267|<br/>
   268|
   269|<p align="center">
   270|  <b>小元读书</b> — <i>Reading, refined.</i>
   271|</p>
   272|