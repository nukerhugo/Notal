# Notal

> A lightweight, distraction-free text editor for Windows — built with Rust.

Created by [Nukerhugo](https://nukerhugo.nl/)

---

## Features

- 🖤 Minimal dark UI — no clutter, just your text
- 📂 Open, Save, Save As with native file dialogs
- 🔍 Find & Replace with match count and case-sensitive option
- 📊 Live line, word, and character count
- 🖱️ Drag & drop files onto the window or the `.exe`
- ⌨️ Keyboard shortcuts for everything
- 📦 Single `.exe`, no installation required

---

## Download

Grab the latest release from the [Releases](../../releases) page.  
No installer — just run `notal.exe`.

---

## Keyboard Shortcuts

| Shortcut       | Action         |
|----------------|----------------|
| Ctrl+N         | New file       |
| Ctrl+O         | Open file      |
| Ctrl+S         | Save           |
| Ctrl+Shift+S   | Save As        |
| Ctrl+F         | Find & Replace |
| Escape         | Close panels   |

---

## Building from Source

You'll need [Rust](https://rustup.rs) installed.

```bash
git clone https://github.com/nukerhugo/Notal.git
cd notal
cargo build --release
```

The binary will be at `target/release/notal.exe`.

---

## Roadmap

- [ ] Syntax highlighting
- [ ] Multiple tabs
- [ ] Line numbers
- [ ] Linux & macOS support
- [ ] Configurable font size and theme

---

## License

Distributed under the **Nukerhugo Source License (NSL) v1.0** — see [`LICENSE`](LICENSE) for full terms.

Personal use is free. For forks, public redistribution, or commercial use, contact via [nukerhugo.nl](https://nukerhugo.nl/).
