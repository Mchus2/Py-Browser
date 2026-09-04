# 🌐 Custom PyQt6 Web Browser

A lightweight, modern, and fast desktop web browser built with Python using **PyQt6** and the **QtWebEngine (Chromium)** engine.

This browser features multi-tab management, built-in multi-language support (English / Polish), basic ad-blocking, session persistence, and custom UI styling.

---

## ✨ Features

* **🚀 Chromium Engine:** Full support for HTML5 video (including YouTube), JavaScript, modern web standards, and full-screen playback.
* **🌍 Automatic & Manual Multi-Language Support (EN / PL):**
  * Automatically detects system language (Windows) on the first run.
  * Instant language toggle button (`🌐 EN / PL`) updating both UI texts and HTTP `Accept-Language` headers to load web pages in your preferred language.
* **🛡️ Built-in AdBlocker:** Intercepts network requests to block common tracking and advertisement domains.
* **📑 Tab Management:**
  * Single-tab creation and a bulk tab opener to open multiple URLs at once.
  * Dynamic tab titles with overflow truncation
* **📺 Fullscreen Mode:** Native support for fullscreen media playback with auto-hiding toolbars.
* **🌙 Dark Theme:** Clean, modern dark UI styling inspired by modern IDEs.

---

## 🛠️ Installation & Setup

### Running via Python

1. Ensure you have Python 3.10+ installed.
2. Install the required dependencies:
   ```bash
   pip install PyQt6 PyQt6-WebEngine
