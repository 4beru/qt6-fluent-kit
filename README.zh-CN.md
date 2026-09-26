<p align="center">
  English | 简体中文
</p>

<h1 align="center">Qt6 Fluent Kit</h1>

<p align="center">
  面向 Qt6 Widgets 的跨平台 Fluent 风格 C++ UI 组件库。
</p>

<p align="center">
  <a href="https://fluentkit.aberu.site/"><strong>项目官网</strong></a>
  ·
  <a href="https://fluentkit.aberu.site/gallery/">Gallery</a>
  ·
  <a href="https://fluentkit.aberu.site/api/">API Explorer</a>
  ·
  <a href="https://github.com/4beru/qt6-fluent-kit/releases">Releases</a>
  ·
  <a href="https://github.com/4beru/qt6-fluent-kit/discussions">Discussions</a>
</p>

Qt6 Fluent Kit（FluentQt）是面向 Qt Widgets 的跨平台 Fluent UI 组件库，提供输入、导航、集合、数据表格、图表、弹窗和窗口等原生控件，并保留 Qt 熟悉的对象模型和 CMake 工作流。

## ✨ 特性

- 跨平台 Qt Widgets 组件
- Fluent 风格视觉语言
- Windows、macOS、Linux 和 WebAssembly
- 浅色、深色和高对比度主题
- 应用级动效策略
- C++17 API
- 可选 PySide6 接口
- CMake 集成
- C++ 与 WebAssembly Gallery
- API Explorer

## 🌐 项目资源

| 资源 | 链接 |
|---|---|
| 官网 | https://fluentkit.aberu.site/ |
| C++ Web Gallery | https://fluentkit.aberu.site/gallery/ |
| API Explorer | https://fluentkit.aberu.site/api/ |
| Releases | https://github.com/4beru/qt6-fluent-kit/releases |
| Discussions | https://github.com/4beru/qt6-fluent-kit/discussions |
| Issues | https://github.com/4beru/qt6-fluent-kit/issues |
| 安全 | [SECURITY.md](SECURITY.md) |
| 支持 | [SUPPORT.md](SUPPORT.md) |

## 📦 安装

### C++ / CMake

正式版本可以通过公开仓库按版本标签集成：

```cmake
include(FetchContent)

FetchContent_Declare(
    fluentqt
    GIT_REPOSITORY https://github.com/4beru/qt6-fluent-kit.git
    GIT_TAG v1.8.5
    GIT_SHALLOW TRUE
)

FetchContent_MakeAvailable(fluentqt)
```

> 公开仓库负责发行版和 Release 入口，实际实现仓库单独维护。

### Python

可选 Python 绑定通过 PyPI 发布：

```bash
python -m pip install FluentQt
```

Gallery 同样可以通过 PyPI 安装：

```bash
python -m pip install FluentQt-Gallery
```

## 📚 文档

完整的面向使用者文档发布在项目官网：

- [项目文档](https://fluentkit.aberu.site/)
- [API Explorer](https://fluentkit.aberu.site/api/)
- [C++ Web Gallery](https://fluentkit.aberu.site/gallery/)

## 🤝 社区

问题、想法和项目讨论请使用 GitHub Discussions；可复现的错误请使用 Issues。

参与项目之前请阅读 [Code of Conduct](CODE_OF_CONDUCT.md)。

## 🔐 安全

请勿通过公开 Issues 或 Discussions 披露安全漏洞。安全问题请按照 [SECURITY.md](SECURITY.md) 中的流程进行私下报告。

## 📄 许可证

Qt6 Fluent Kit 自有源代码采用 MIT License。捆绑资产和运行时依赖继续遵循其上游许可证，请参阅 [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)。

## ™️ 商标

有关项目身份、第三方商标和外部设计参考的信息，请参阅 [TRADEMARKS.md](TRADEMARKS.md)。
