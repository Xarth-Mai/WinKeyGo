# WinKeyGo

🚀 **WinKeyGo** is a lightweight and user-friendly Windows hotkey launcher built with Rust.

---

## ✨ Features

* 🧩 **Custom Hotkeys**: Define custom hotkeys to launch any app, folder, or URL.
* 🖼️ **Intuitive GUI**: Simple and intuitive graphical user interface.
* 💾 **Auto-save Configuration**: Auto-save configuration with import/export support.
* 🔧 **System Tray Operation**: Runs in the system tray, background friendly.
* 🚀 **Auto-start on Boot**: Optional auto-start on boot.

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

1. Launch WinKeyGo and click "Add Hotkey".
2. Choose a key combination (e.g., `Ctrl+Alt+N`).
3. Select the target app or file to launch.
4. Save, and the hotkey takes effect immediately.

---

## 💡 Roadmap

* [ ] Hotkey registration and handling
* [ ] GUI interface
* [ ] Auto-start support
* [ ] System tray integration
* [ ] Hotkey conflict detection

---

## 🛠 Tech Stack

* **Language**: [Rust](https://github.com/rust-lang/rust)
* **GUI Framework**: [egui](https://github.com/emilk/egui)
* **Hotkey Handler**: [windows-hotkeys](https://github.com/dnlmlr/windows-hotkeys)

---

## 📃 License

Released under the [MPL-2.0 license](LICENSE).
