# Origo Reader

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,50:1a1020,100:0a0a0a&height=220&section=header&text=小元读书&fontSize=60&fontColor=e8c4f0&fontAlignY=38&desc=Origo%20Reader%20%E2%80%94%20Reading%2C%20refined.&descSize=18&descAlignY=62&descAlign=50&animation=fadeIn" width="100%" />
</p>

<p align="center">
  <b>专注阅读本身的电子书阅读器</b><br/>
  <sub>不社交 · 不弹窗 · 不开屏广告 · 只安静地读书</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Project-Monorepo-purple?style=flat-square" />
  <img src="https://img.shields.io/badge/Versions-2-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Platforms-5-brightgreen?style=flat-square" />
  <a href="https://github.com/KeloYuan/Origo-Reader/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-yellow?style=flat-square" /></a>
  <img src="https://img.shields.io/github/stars/KeloYuan/Origo-Reader?style=flat-square&logo=github&color=FFD600" />
</p>

<p align="center">
  <b>English</b> · <a href="#-关于小元读书">中文</a>
</p>

<br/>

> **Origo Reader** is a cross-platform ebook reader that puts reading first.  
> Two editions — one open-source Flutter app covering 5 platforms, one native Swift app optimized for Apple.  
> No social features. No ads. No distractions. Just books.

<br/>

<p align="center">
  <b>小元读书</b> 有两个版本，共享同一个愿景，面向不同的使用场景。
</p>

<table>
  <tr>
    <th width="4%"></th>
    <th width="48%" align="center">
      <img src="https://img.shields.io/badge/-Open_Reading-00C853?style=for-the-badge&logo=open-source-initiative&logoColor=white" /><br/>
      <sub>开源跨平台版</sub>
    </th>
    <th width="48%" align="center">
      <img src="https://img.shields.io/badge/-Origo-7C4DFF?style=for-the-badge&logo=apple&logoColor=white" /><br/>
      <sub>原生 iOS / macOS 版</sub>
    </th>
  </tr>
  <tr>
    <td><b>技术栈</b></td>
    <td align="center">
      <img src="https://img.shields.io/badge/Flutter-3.35-blue?style=flat&logo=flutter" />
      <img src="https://img.shields.io/badge/Dart-3.9-0175C2?style=flat&logo=dart" />
      <img src="https://img.shields.io/badge/Rust-da4326?style=flat&logo=rust" />
    </td>
    <td align="center">
      <img src="https://img.shields.io/badge/Swift-5-orange?style=flat&logo=swift" />
      <img src="https://img.shields.io/badge/SwiftUI-blue?style=flat" />
      <img src="https://img.shields.io/badge/CoreText-333?style=flat" />
    </td>
  </tr>
  <tr>
    <td><b>平台</b></td>
    <td align="center">
      Android · iOS · macOS · Windows · Linux
    </td>
    <td align="center">
      iOS · macOS
    </td>
  </tr>
  <tr>
    <td><b>开源</b></td>
    <td align="center">✅ MIT</td>
    <td align="center">🔒 闭源</td>
  </tr>
  <tr>
    <td><b>格式</b></td>
    <td align="center">EPUB · PDF · TXT · ZIP</td>
    <td align="center">EPUB · PDF · TXT</td>
  </tr>
  <tr>
    <td><b>仓库</b></td>
    <td align="center"><a href="https://github.com/KeloYuan/open-reading">→ <b>open-reading</b></a></td>
    <td align="center">本仓库</td>
  </tr>
</table>

<br/>

---

<br/>

## 🟢 Open Reading — 开源跨平台版

<p align="center">
  <a href="https://github.com/KeloYuan/open-reading">
    <img src="https://img.shields.io/badge/🔗_源码仓库-open--reading-00C853?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

> 基于 Flutter 构建，一套代码覆盖五个平台。  
> 核心解析引擎使用 Rust 编写，兼顾性能与跨平台一致性。

<br/>

<table>
  <tr>
    <td width="50%" valign="top">

#### 📖 阅读体验
- 📄 多格式 — EPUB · PDF · TXT · ZIP
- 📐 二分搜索精准分页
- 🔄 翻页 / 滑动 / 滚动 / 3D 仿真
- 🎨 多种阅读主题 + 自定义
- 🔤 字号 · 行距 · 字距 · 缩进
- 🌙 护眼暗色模式

</td>
    <td width="50%" valign="top">

#### 🛠️ 智能工具
- 🔖 书签 · 一键快速跳转
- ✏️ 高亮标注 + 笔记
- 🔊 TTS 朗读 + 逐句高亮
- 📊 阅读统计可视化
- ☁️ WebDAV 全量同步
- 🦀 Rust 核心引擎

</td>
  </tr>
</table>

```bash
git clone https://github.com/KeloYuan/open-reading.git && cd open-reading
flutter pub get && flutter run
```

<p align="center">
  <sub>👉 详细文档、安装包、路线图请前往 <a href="https://github.com/KeloYuan/open-reading"><b>open-reading</b></a></sub>
</p>

<br/>

---

<br/>

## 🟣 Origo — 原生 iOS / macOS 版

> 用 Swift 从零构建，为 Apple 生态深度优化的阅读体验。

<br/>

### 为什么还需要一个原生版本？

Flutter 版已经足够好用，但原生版能做到：

- **真实排版** — CoreText 逐字排版，TXT 分页结果来自真实设备渲染，不是估算
- **零桥接开销** — 纯 SwiftUI，每个交互都丝滑到像素级
- **深度系统集成** — Share Sheet · Spotlight 搜索 · Shortcuts 快捷指令 · Widget
- **极致首屏** — 章节索引缓存 + 窗口化分页，打开就看，不等待

<br/>

### 核心能力

<table>
  <tr>
    <td width="33%" valign="top" align="center">

#### 📖 原生阅读
Swift CoreText 逐字排版  
真实设备页码  
不依赖 WebView  
滑动零掉帧

</td>
    <td width="33%" valign="top" align="center">

#### 🎯 CanonicalLocator
进度 · 书签 · 高亮的唯一真相源  
换字号、换设备均可恢复  
设备无关的文本锚定

</td>
    <td width="33%" valign="top" align="center">

#### 🤖 AI 阅读助手
原生集成，随时问答  
选中文字即可解释  
全文知识对话

</td>
  </tr>
  <tr>
    <td valign="top" align="center">

#### ☁️ Supabase 同步
书库 · 进度 · 笔记  
跨设备无缝衔接

</td>
    <td valign="top" align="center">

#### 📊 阅读统计
每日 / 每周 / 每月  
阅读时长与趋势

</td>
    <td valign="top" align="center">

#### 🔊 原生 TTS
逐句朗读  
进度实时同步  
语速 · 音调可调

</td>
  </tr>
</table>

<br/>

### 架构

```
Origo Reader/
├── App/            # 入口 · 依赖组合根
├── Features/       # 页面 — AI · 书库 · 阅读器 · 笔记 · 设置 · 统计
├── Core/           # 能力 — Reader · Sync · API · Auth · Networking
├── Data/           # 数据 — 持久化 · DAO · 模型
├── DesignSystem/   # 设计系统
├── Models/         # 领域模型
├── Services/       # 业务服务
└── Resources/      # 资源文件
```

<br/>

### 技术选型

| 层级 | 选择 | 理由 |
|------|------|------|
| UI | SwiftUI | 声明式，Apple 原生，动画流畅 |
| TXT 排版 | CoreText | 逐字控制，真实页码，零依赖 |
| EPUB / PDF | Readium Swift Toolkit | 成熟开源方案 |
| 云同步 | Supabase | 实时同步 + Auth + Storage |
| 定位系统 | CanonicalLocator | 自研，设备无关文本锚定 |
| 分页 | 窗口化 + 后台预排 | 首屏秒开，滑动不掉帧 |

<br/>

### 状态

> 🚧 积极开发中，暂未公开发布。  
> 如需体验，请关注本仓库的 [Releases](https://github.com/KeloYuan/Origo-Reader/releases) 动态。

<br/>

---

<br/>

## 🏷️ 为什么选择小元读书

<table>
  <tr>
    <td width="50%" valign="top">

#### 读得舒服
- 📐 分页精准，不跳不闪不抖
- 🎨 主题丰富，深色护眼
- 🔤 字体字号行距全可调
- 📄 EPUB / PDF / TXT 全支持

</td>
    <td width="50%" valign="top">

#### 用得省心
- 🔖 书签 · 标注 · 笔记一应俱全
- ☁️ WebDAV / Supabase 跨设备同步
- 🔊 TTS 朗读，解放双眼
- 📊 阅读数据，量化你的成长

</td>
  </tr>
  <tr>
    <td valign="top">

#### 安静纯粹
- ✅ 无社交 · 无弹窗 · 无广告
- ✅ 打开就读书，零学习成本
- ✅ 不收集数据，不推送通知

</td>
    <td valign="top">

#### 技术扎实
- 🦀 Rust 核心引擎，性能优先
- 📱 原生 + 跨平台双版本
- 🔓 MIT 开源，社区共建

</td>
  </tr>
</table>

<br/>

---

<br/>

## 🌍 关于小元读书

<p align="center">
  <b>让阅读回归阅读本身。</b>
</p>

<p align="center">
  排版好不好看 · 翻页顺不顺手 · 笔记好不好找<br/>
  <sub>—— 这些才是阅读器该关心的事。</sub>
</p>

<br/>

## ⭐ Star History

<p align="center">
  <a href="https://star-history.com/#KeloYuan/Origo-Reader&Date">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=KeloYuan/Origo-Reader&type=Date&theme=dark" />
      <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=KeloYuan/Origo-Reader&type=Date" />
      <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=KeloYuan/Origo-Reader&type=Date" width="600" />
    </picture>
  </a>
</p>

<br/>

<p align="center">
  <a href="https://github.com/KeloYuan/open-reading/stargazers">
    <img src="https://img.shields.io/badge/⭐_Star_支持-open--reading-FFD600?style=for-the-badge&logo=github&logoColor=black" />
  </a>
</p>

<br/>

<p align="center">
  <b>小元读书</b> — <i>Reading, refined.</i>
</p>
