# Kiro Token Manager

一款 Kiro Token 管理工具，帮助用户更方便地管理和查看自己的 Token 信息。

## 功能特性

- **Token 管理** - 导入和管理您的 Kiro Token
- **用量查询** - 实时查询 Token 用量和额度信息
- **自动刷新** - 自动刷新过期的 Token
- **数据持久化** - 用量数据本地保存，离线也能查看
- **深色模式** - 支持深色主题

## 下载安装

前往 [Releases](../../releases) 页面下载最新版本。

### Windows
- `KiroTokenManager_版本_x64_portable.zip` - 便携版（需要系统已安装 WebView2）

### macOS
- `KiroTokenManager_版本_aarch64.dmg` - Apple Silicon (M1/M2/M3/M4)
- `KiroTokenManager_版本_x64.dmg` - Intel

### Linux
- `KiroTokenManager_版本_amd64.deb` - Debian/Ubuntu
- `KiroTokenManager_版本_x86_64.rpm` - Fedora/RHEL

## 快速开始

1. 下载并安装应用
2. 点击"导入"按钮，粘贴 Token JSON 数据
3. 点击刷新按钮查询用量

## 常见问题

**Q: Token 从哪里获取？**  
A: Token 存储在 `~/.aws/sso/cache/kiro-auth-token.json` 文件中。

**Q: Token 过期了怎么办？**  
A: 点击刷新按钮，应用会自动刷新 Token。

## 系统要求

- Windows 10+ (x64)
- macOS 10.15+
- Linux (x64)

## 免责声明

本工具仅供个人学习和研究使用。用户在使用本工具时，应遵守相关服务的使用条款和法律法规。开发者不对因使用本工具而产生的任何问题承担责任。
