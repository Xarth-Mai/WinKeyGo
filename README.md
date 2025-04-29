# WinKeyGo

🚀 **WinKeyGo** is a lightweight and user-friendly Windows hotkey launcher built with Rust.

---

## ✨ Features

- 🧩 Define custom hotkeys to launch any app, folder, or URL
- 🖼️ Simple and intuitive graphical user interface
- 💾 Auto-save configuration with import/export support
- 🔧 Runs in the system tray, background friendly
- 🚀 Optional auto-start on boot

---

## 📦 Installation

### Download Release (Recommended)

Go to [Releases](https://github.com/Xarth-Mai/WinKeyGo/releases) and download the latest `.zip` file. Extract and run `WinKeyGo.exe`.

### Build with Cargo (Developers)

```bash
git clone https://github.com/Xarth-Mai/WinKeyGo.git
cd WinKeyGo
cargo run --release
```

---

## 🧰 Quick Start

1. Launch WinKeyGo and click "Add Hotkey"
2. Choose a key combination (e.g. `Ctrl+Alt+N`)
3. Select the target app or file to launch
4. Save and the hotkey takes effect immediately

---

## 💡 Roadmap

- [ ] Hotkey registration and handling
- [ ] GUI interface
- [ ] Auto-start support
- [ ] System tray integration
- [ ] Hotkey conflict detection

---

## 🛠 Tech Stack

- Rust
- [`windows`](https://crates.io/crates/windows) crate (Win32 API)

---

## 📃 License

Released under the [MPL-2.0 license](LICENSE).
