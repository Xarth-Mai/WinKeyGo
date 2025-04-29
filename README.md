# WinKeyGo

🚀 **WinKeyGo** 是一个用 Rust 编写的 Windows 快捷键工具，允许你为任意程序或文件设置自定义快捷键，一键启动，高效办公。

---

## ✨ 功能特点

- 🧩 自定义快捷键，启动任意程序、文件夹或网页
- 🖼️ 简洁易用的图形界面
- 💾 自动保存配置，支持导入导出
- 🔧 系统托盘常驻，可后台运行
- 🚀 支持开机自启

---

## 📦 安装方式

### 下载 Release 版本（建议）
前往 [Releases](https://github.com/Xarth-Mai/WinKeyGo/releases) 下载最新版本的 `.zip` 包，解压后运行 `WinKeyGo.exe` 即可。

### 使用 Cargo 构建（开发者）

```bash
git clone https://github.com/Xarth-Mai/WinKeyGo.git
cd winkeygo
cargo run --release
```

---

## 🧰 快速上手

1. 打开 WinKeyGo，点击 “添加快捷键”
2. 选择一个快捷键组合（如 `Ctrl+Alt+N`）
3. 选择要启动的目标程序或文件
4. 点击保存，即可生效

---

## 💡 路线图

- [ ] 快捷键注册与监听
- [ ] GUI 界面
- [ ] 自启动设置
- [ ] 系统托盘支持
- [ ] 快捷键冲突检测

---

## 🛠 技术栈

- Rust
- `windows` crate（Win32 API）

---

## 📃 许可证

[MPL-2.0 license](LICENSE)
