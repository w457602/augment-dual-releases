# AugmentInjector - 官方发布版本

🚀 **跨平台 VS Code Augment 注入管理器**

## 📦 下载最新版本

请前往 [Releases](https://github.com/w457602/augment-dual-releases/releases) 页面下载适合您系统的版本。

### 支持的平台

#### Windows
- **Windows 64位 (x64)**: `AugmentInjector-windows-x64.exe`
- **Windows 32位 (x86)**: `AugmentInjector-windows-x86.exe`

#### Linux  
- **Linux 64位 (x64)**: `AugmentInjector-linux-x64` 或 `AugmentInjector-linux-x64.AppImage`

#### macOS
- **macOS Intel芯片**: `AugmentInjector-macos-intel`
- **macOS Apple芯片 (M1/M2/M3)**: `AugmentInjector-macos-apple-silicon`

## 🔍 如何选择正确的版本？

**Windows用户**:
- 大多数现代Windows系统使用64位版本
- 如果你的系统较老或明确是32位，选择x86版本

**macOS用户**:
- 2020年后的Mac (M1/M2/M3芯片): 选择Apple芯片版本
- 2020年前的Mac (Intel芯片): 选择Intel版本
- 不确定？在终端运行 `uname -m`，显示`arm64`选Apple芯片版本，显示`x86_64`选Intel版本

**Linux用户**:
- 大多数现代Linux系统使用x64版本
- AppImage版本无需安装，直接运行

## 🔧 支持的编辑器

- Visual Studio Code
- Cursor
- Windsurf
- VSCodium
- Code-OSS
- Kiro

## 📋 使用说明

1. 下载对应平台的可执行文件
2. 双击运行（Linux/macOS 可能需要添加执行权限）
3. 在Web界面中选择编辑器和注入模式

## ⚠️ 注意事项

- 使用前请确保目标编辑器已完全关闭
- 首次使用会自动创建备份文件
- 如遇问题可使用恢复功能

## 🐛 问题反馈

如果您在使用过程中遇到问题，请在 [Issues](https://github.com/w457602/augment-dual-releases/issues) 页面提交反馈。

---

**注意**: 这是专门的发布仓库，仅包含编译后的可执行文件，不包含源代码。
