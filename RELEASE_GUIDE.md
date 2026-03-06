# 如何创建 GitHub Release 并上传安装包

由于安装包文件较大（超过 100MB），需要通过 GitHub Releases 功能上传。

## 📋 步骤

### 1. 访问 Releases 页面

访问：https://github.com/ModelSmart/MaudelClaw/releases/new

### 2. 填写 Release 信息

- **Tag version**: `v1.5.4`
- **Release title**: `MaudelClaw v1.5.4`
- **Describe this release**: 复制以下内容：

```markdown
# MaudelClaw v1.5.4 Release Notes

**Release Date**: March 6, 2026

## 🎉 Highlights

- ✨ Enhanced UI/UX with smoother animations
- ⚡ Better performance and optimized memory usage
- 🔧 Support for more AI models and tools

## 📦 Installation Packages

### macOS
- **MaudelClaw_1.5.4_AppleSilicon.dmg** (192 MB) - For Apple Silicon Macs (M1/M2/M3)
- **MaudelClaw_1.5.4_x64.dmg** (203 MB) - For Intel-based Macs

### Windows
- **MaudelClaw_1.5.4_x64-setup.exe** (140 MB) - Windows 10/11 installer

## 📋 System Requirements

### macOS
- macOS 10.15 (Catalina) or later
- 8GB RAM (16GB recommended)

### Windows
- Windows 10 or later (64-bit)
- 8GB RAM (16GB recommended)

## 🚀 Quick Start

1. Download the installer for your platform
2. Run the installer
3. Launch MaudelClaw and start!

## 🔐 Security

- All packages are code-signed
- No telemetry or data collection
- Your data stays local

---

**Website**: https://maudel.ai
```

### 3. 上传安装包文件

在 "Attach binaries" 区域，拖拽或选择以下文件：

1. `/Users/leo/Work/Halo/Apple密钥/MaudelClaw_1.5.4_AppleSilicon.dmg`
2. `/Users/leo/Work/Halo/Apple密钥/MaudelClaw_1.5.4_x64.dmg`
3. `/Users/leo/Work/Halo/Apple密钥/MaudelClaw_1.5.4_x64-setup.exe`

### 4. 发布

点击 **Publish release** 按钮

## ✅ 发布后

Release 创建后，用户可以：
- 在 https://github.com/ModelSmart/MaudelClaw/releases 看到所有版本
- 直接下载安装包
- README 中的下载链接会自动指向最新版本

## 📌 提示

- 每个 Release 最多可上传 2GB 文件
- 建议勾选 "Set as the latest release"
- 可以保存为 Draft 先预览效果
