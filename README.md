# 小元读书 (Origo Reader)

## 这个仓库会发Release，源代码会在APP上架App Store后开源
优雅的 Flutter 跨平台电子书阅读器，支持多种书籍格式，提供舒适的阅读体验。

![Flutter](https://img.shields.io/badge/Flutter-3.35.3-blue)
![License](https://img.shields.io/badge/License-Private-red)
![Platform](https://img.shields.io/badge/Platform-iOS%20%7C%20Android%20%7C%20Windows%20%7C%20macOS%20%7C%20Linux-lightgrey)

---

## 功能清单

### 格式支持

| 功能 | 状态 | 说明 |
|------|------|------|
| EPUB 格式 | ✅ 完成 | 完整的 EPUB 电子书支持，图片提取 |
| PDF 格式 | ✅ 完成 | 原生 PDF 渲染阅读 |
| TXT 格式 | ✅ 完成 | 编码检测、智能章节提取 |
| ZIP 压缩包 | ✅ 完成 | 支持导入压缩包内的电子书 |

### 阅读体验

| 功能 | 状态 | 说明 |
|------|------|------|
| 智能分页 | ✅ 完成 | 二分法高性能分页，渐进式加载 |
| 翻页模式 - 覆盖 | ✅ 完成 | 模拟真实翻页效果 |
| 翻页模式 - 滑动 | ✅ 完成 | 左右滑动切换 |
| 翻页模式 - 滚动 | ✅ 完成 | 连续滚动模式 |
| 翻页模式 - 仿真 | ✅ 完成 | 3D 翻页动画 |
| 阅读主题 | ✅ 完成 | 8 种预设 + 自定义主题 |
| 字体调节 | ✅ 完成 | 字体大小、行距、字间距、首行缩进 |
| 音量键翻页 | ✅ 完成 | 硬件按键支持 |
| 沉浸式阅读 | ✅ 完成 | 全屏模式，自动隐藏系统栏 |
| 目录导航 | ✅ 完成 | 章节快速跳转 |
| 图片显示 | ✅ 完成 | EPUB 图片渲染 |

### 书签笔记

| 功能 | 状态 | 说明 |
|------|------|------|
| 添加书签 | ✅ 完成 | 快速标记位置 |
| 书签管理 | ✅ 完成 | 列表查看、跳转 |
| 文本高亮 | ✅ 完成 | 多颜色高亮支持 |
| 添加笔记 | ✅ 完成 | 高亮关联笔记 |
| 阅读进度 | ✅ 完成 | 自动保存位置 |

### TTS 朗读

| 功能 | 状态 | 说明 |
|------|------|------|
| 系统 TTS | ✅ 完成 | Android TTS / iOS AVSpeechSynthesizer |
| 语速调节 | ✅ 完成 | 可调节朗读速度 |
| 音量调节 | ✅ 完成 | 可调节朗读音量 |
| 音调调节 | ✅ 完成 | 可调节朗读音调 |
| 定时停止 | ✅ 完成 | 睡眠定时功能 |
| 句子高亮 | ✅ 完成 | 朗读时高亮当前句子 |

### 数据统计

| 功能 | 状态 | 说明 |
|------|------|------|
| 阅读时长统计 | ✅ 完成 | 按日/周/月统计 |
| 阅读进度追踪 | ✅ 完成 | 书籍进度可视化 |
| 阅读历史 | ✅ 完成 | 历史记录查询 |
| 统计图表 | ✅ 完成 | fl_chart 图表展示 |

### 数据同步

| 功能 | 状态 | 说明 |
|------|------|------|
| WebDAV 同步 | ✅ 完成 | 云端备份与恢复 |
| 书籍元数据同步 | ✅ 完成 | 书名、作者等信息 |
| 进度同步 | ✅ 完成 | 阅读位置同步 |
| 书签笔记同步 | ✅ 完成 | 高亮书签云端同步 |
| 冲突处理 | ✅ 完成 | 时间戳自动合并 |

### 书源管理

| 功能 | 状态 | 说明 |
|------|------|------|
| 书源添加 | ✅ 完成 | 自定义书源配置 |
| 书源启用 | ✅ 完成 | 启用/禁用书源 |
| 书源编辑 | ✅ 完成 | 修改书源信息 |
| 书源删除 | ✅ 完成 | 移除书源 |

### 系统功能

| 功能 | 状态 | 说明 |
|------|------|------|
| 文件导入 | ✅ 完成 | 本地文件系统导入 |
| 书籍封面 | ✅ 完成 | 自动生成封面 |
| 响应式布局 | ✅ 完成 | 手机/平板自适应 |
| 国际化 | ✅ 完成 | 中文/英文支持 |
| 增量更新 | ✅ 完成 | 内容哈希检测 |

### 平台支持

| 平台 | 状态 | 说明 |
|------|------|------|
| Android | ✅ 完成 | 最低 API 21 |
| iOS | ✅ 完成 | 最低 iOS 11.0 |
| Windows | ✅ 完成 | 桌面平台完整支持 |
| macOS | ✅ 完成 | 桌面平台完整支持 |
| Linux | ✅ 完成 | 桌面平台完整支持 |

---

## 待完成功能

### 核心功能

| 功能 | 优先级 | 说明 |
|------|--------|------|
| 书源搜索 | 🔴 高 | 通过书源搜索书籍 |
| 书源阅读 | 🔴 高 | 从书源在线阅读/下载 |
| 网络书籍导入 | 🟡 中 | URL 导入网络资源 |

### 阅读体验

| 功能 | 优先级 | 说明 |
|------|--------|------|
| 滚动翻页优化 | 🟡 中 | 滚动模式性能优化 |
| PDF 目录跳转 | 🟡 中 | PDF 章节导航 |
| PDF 缩放 | 🟡 中 | PDF 查看缩放 |

### 同步功能

| 功能 | 优先级 | 说明 |
|------|--------|------|
| iCloud 同步 | 🟡 中 | Apple 生态同步 |
| 本地备份 | 🟡 中 | JSON/数据库导出导入 |

### 其他

| 功能 | 优先级 | 说明 |
|------|--------|------|
| 夜间模式全局开关 | 🟢 低 | 设置页一键切换 |
| 字体自定义 | 🟢 低 | 导入自定义字体 |
| 书籍排序 | 🟢 低 | 多维度排序选项 |

---

## 技术栈

### 核心框架
- **Flutter** `3.35.3` - 跨平台 UI 框架
- **Dart** `3.9.2` - 编程语言
- **Riverpod** `2.6.1` - 状态管理

### 数据层
- **SQLite** (`sqflite`) - 本地数据库
- **SharedPreferences** - 配置存储
- **Path Provider** - 文件路径管理

### 文件处理
- **EPUBX** - EPUB 格式解析
- **PDFX** - PDF 渲染
- **_archive** - ZIP 压缩包处理

### UI 组件
- **Material 3** - Google 设计语言
- **FL Chart** - 图表展示
- **flutter_svg** - SVG 渲染

---

## 项目结构

```
lib/
├── main.dart                    # 应用入口，主题配置
├── models/                      # 数据模型层
│   ├── book.dart               # 书籍模型
│   ├── chapter.dart            # 章节模型
│   ├── bookmark.dart           # 书签模型
│   ├── book_note.dart          # 笔记/高亮模型
│   ├── book_source.dart        # 书源模型
│   ├── page_turning_config.dart # 翻页配置
│   └── text_page_data.dart     # 文本页面数据
├── pages/                       # 页面组件层
│   ├── reader_page.dart        # 阅读页面（核心）
│   ├── home_shell_page.dart    # 首页容器
│   ├── home_dashboard_page.dart # 首页内容
│   ├── library_page.dart       # 书库页面
│   ├── import_book_page.dart   # 导入书籍页面
│   ├── settings_page.dart      # 设置页面
│   ├── book_source_page.dart   # 书源管理页面
│   └── detailed_stats_page.dart # 详细统计页面
├── providers/                   # 状态管理
│   └── reader_providers.dart   # 阅读器核心 Provider
├── services/                    # 业务逻辑层
│   ├── books/                  # 书籍相关服务
│   │   ├── book_import_service.dart      # 书籍导入
│   │   ├── enhanced_txt_import_service.dart # TXT 导入
│   │   ├── book_dao.dart                 # 数据访问
│   │   └── epub_image_extractor_service.dart # EPUB 图片
│   ├── pagination/             # 分页系统
│   │   ├── enhanced_paginator_service.dart # 核心分页器
│   │   ├── pagination_cache_service.dart   # 分页缓存
│   │   └── text_preprocessor_helper.dart   # 文本预处理
│   ├── reading/                # 阅读功能
│   │   ├── reading_router_service.dart    # 阅读路由
│   │   ├── reading_progress_service.dart   # 阅读进度
│   │   └── reader_settings_service.dart   # 阅读设置
│   ├── tts/                    # TTS 朗读
│   │   ├── base_tts.dart       # TTS 基类
│   │   ├── system_tts.dart     # 系统 TTS 实现
│   │   └── tts_preferences.dart # TTS 设置
│   └── sync/                   # 同步模块
│       └── webdav_sync_service.dart # WebDAV 同步
├── utils/                       # 工具类层
│   ├── app_themes.dart        # 应用主题
│   ├── layout_helper.dart      # 响应式布局
│   ├── page_transitions.dart   # 页面转场
│   └── glass_config.dart      # 毛玻璃效果
└── widgets/                     # 自定义组件
    ├── toc_widget.dart         # 目录组件
    ├── tts_settings_sheet.dart # TTS 设置面板
    ├── page_turning_settings_sheet.dart # 翻页设置
    ├── enhanced_text_selection_toolbar.dart # 文本选择
    └── webdav_config_dialog.dart # WebDAV 配置
```

---

## 快速开始

### 环境要求
- Flutter SDK `3.35.3+`
- Dart SDK `3.9.2+`
- Android Studio / VS Code

### 安装步骤

```bash
# 克隆项目
git clone <repository-url>
cd xxread

# 安装依赖
flutter pub get

# 调试运行
flutter run

# 发布构建
flutter build apk        # Android
flutter build ios        # iOS
flutter build windows    # Windows
flutter build macos     # macOS
flutter build linux      # Linux
```

---

## 许可证

此项目为私有项目。

---

**小元读书** - 让阅读更加优雅 📚✨
