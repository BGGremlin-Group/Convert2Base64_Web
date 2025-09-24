# Convert2Base64 💾⚡

Single-file web encoder by the **Background Gremlin Group** (*BGGG*)  
Drop any file → instant Base-64, raw SVG, CSS or HTML. No installs, no servers, just vibes.

![version](https://img.shields.io/badge/version-3.0.0-39ff14?style=flat-square)
![license](https://img.shields.io/badge/license-MIT-00ffff?style=flat-square)

---

## 🚀 Quick Start

1. Grab [`Convert 2 Web Pro.html`](https://github.com/BGGremlin-Group/Convert2Base64_Web/releases/latest)
2. Double-click → page opens (works offline too)
3. Drag file(s) onto the CRT screen
4. Pick output format → auto-download starts

---

## ✨ Features

| | |
|-|-|
| ⚡ **Zero-deps** | Only Three.js CDN (graceful fallback) |
| 🎯 **4 outputs** | Base-64 URI, raw SVG, CSS class, HTML tag |
| 📁 **Batch** | Drop many files → queued downloads |
| 🖥️ **CRT skin** | Retro terminal + scan-lines + glitch fx |
| ⌨️ **Hot-keys** | `D` redact / `G` glitch / `S` scroll / `H` help |
| 🌐 **Offline** | Runs from USB, no server needed |

---

## 📤 Output Formats

| Radio | File suffix | What you get |
|-------|-------------|--------------|
| **B64** 📄 | `.txt` | `data:image/...;base64,...` ready to paste |
| **RAW** 📝 | `_RAW.svg` | Clean UTF-8 SVG markup |
| **CSS** 🎨 | `.css` | `.filename{ background:url(...) ... }` |
| **HTML** 🖼️ | `.html` | `<img src="..." alt="filename" />` |

---

## 🕹️ Keyboard Easter-Eggs

| Key | Effect |
|-----|--------|
| `D` | Toggle **redacted** colour scheme |
| `G` | 300 ms screen **glitch** |
| `S` | Toggle console **auto-scroll** |
| `H` | Show hot-key list |

---

## 🌟 Change Log

### v3.0.0 Pro (latest)
- Added CSS & HTML quick-export radios  
- Improved queue counter & logging  
- Unified blob saver

### v2.0.0 webV2
- Toggle Base-64 ↔ raw SVG  
- Retained CRT UI + Three.js scene

### v1.0.0 web
- Initial release  
- File → Base-64 data-uri only  
- Drag-and-drop + glitch easter-eggs

---

## 🧪 Browser Support

Chrome 60+ ∙ Firefox 55+ ∙ Safari 11+ ∙ Edge 79+  
(needs ES-6 `async/await` + `FileReader`)

---

## 📦 Repo

[https://github.com/BGGremlin-Group/Convert2Base64_Web](https://github.com/BGGremlin-Group/Convert2Base64_Web)  
Issues & PRs welcome 🎉

---

## 📜 License

MIT © Background Gremlin Group
*Creating Unique Tools for Unique Individuals*
