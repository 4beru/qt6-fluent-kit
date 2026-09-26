<p align="center">
  <img src="https://fluentkit.aberu.site/favicon.svg" width="88" alt="Qt6 Fluent Kit logo">
</p>

<h1 align="center">Qt6 Fluent Kit</h1>

<p align="center">
  A cross-platform Fluent-style C++ UI component library for Qt6 Widgets.
</p>

<p align="center">
  <a href="https://fluentkit.aberu.site/"><strong>Website</strong></a>
  ·
  <a href="https://fluentkit.aberu.site/gallery/">Gallery</a>
  ·
  <a href="https://fluentkit.aberu.site/api/">API Explorer</a>
  ·
  <a href="https://github.com/4beru/qt6-fluent-kit/releases">Releases</a>
  ·
  <a href="https://github.com/4beru/qt6-fluent-kit/discussions">Discussions</a>
</p>

Qt6 Fluent Kit (FluentQt) is a cross-platform Fluent UI component library for Qt Widgets. It provides native controls for input, navigation, collections, data grids, charts, overlays, and windows while preserving Qt's object model and CMake workflow.

## ✨ What it provides

- Cross-platform Qt Widgets components
- Fluent-style visual language
- Windows, macOS, Linux and WebAssembly support
- Light, Dark and High Contrast themes
- Application-wide motion policies
- C++17 API
- Optional PySide6 bindings
- CMake-based integration
- C++ and WebAssembly Gallery
- API reference and interactive component explorer

## 🌐 Project resources

| Resource | Link |
|---|---|
| Website | https://fluentkit.aberu.site/ |
| C++ Web Gallery | https://fluentkit.aberu.site/gallery/ |
| API Explorer | https://fluentkit.aberu.site/api/ |
| Releases | https://github.com/4beru/qt6-fluent-kit/releases |
| Discussions | https://github.com/4beru/qt6-fluent-kit/discussions |
| Issues | https://github.com/4beru/qt6-fluent-kit/issues |
| Security | [SECURITY.md](SECURITY.md) |
| Support | [SUPPORT.md](SUPPORT.md) |

## 📦 Installation

### C++ / CMake

For a versioned integration, use the public repository as the Git source for a release:

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

> The public repository is the distribution and release reference for Qt6 Fluent Kit. The implementation repository is maintained separately.

### Python

The optional Python bindings are distributed through PyPI:

```bash
python -m pip install FluentQt
```

Gallery packages are available through PyPI as well:

```bash
python -m pip install FluentQt-Gallery
```

## 📚 Documentation

The complete reader-facing documentation is published through the project website.

- [Documentation](https://fluentkit.aberu.site/)
- [API Explorer](https://fluentkit.aberu.site/api/)
- [C++ Web Gallery](https://fluentkit.aberu.site/gallery/)

## 🤖 AI-assisted development

Qt6 Fluent Kit includes guidance for AI coding agents and machine-readable API information. The website is the public entry point for these resources.

## 🤝 Community

Use GitHub Discussions for questions, ideas and project conversations. Use Issues for reproducible bugs and focused changes.

Please read the [Code of Conduct](CODE_OF_CONDUCT.md) before participating.

## 🔐 Security

Do not disclose security vulnerabilities through public Issues or Discussions. Follow [SECURITY.md](SECURITY.md) for the private reporting process.

## 📄 License

Qt6 Fluent Kit's own source code is released under the MIT License. Bundled assets and runtime dependencies retain their upstream terms; see [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

## ™️ Trademarks

See [TRADEMARKS.md](TRADEMARKS.md) for information about project identity, third-party trademarks and external design references.
