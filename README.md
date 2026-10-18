<p align="center">
  <img src="assets/opencode_ad.png" alt="OpenCode Agent for Android" width="100%" />
</p>

<h1 align="center">OpenCode Agent for Android</h1>

<p align="center">
  <strong>Turn your Android phone or tablet into a 24/7 autonomous AI coding and Linux workspace powerhouse.</strong><br>
  <em>Official arm64 Ubuntu 24.04 Linux engine • 100+ Models (DeepSeek-R1 / Claude 3.7 / Ollama) • Zero Root Required.</em>
</p>

<p align="center">
  <a href="https://url.userdeep.com/oc-github-readme"><img src="https://img.shields.io/badge/Google%20Play-Download%20Now-brightgreen?style=for-the-badge&logo=google-play" alt="Google Play"></a>
  <a href="https://opencode.userdeep.com/"><img src="https://img.shields.io/badge/Website-opencode.userdeep.com-blue?style=for-the-badge&logo=google-chrome" alt="Website"></a>
  <img src="https://img.shields.io/badge/Android-8.0%2B-green?style=for-the-badge&logo=android" alt="Android 8.0+">
  <img src="https://img.shields.io/badge/Root-Not%20Required-success?style=for-the-badge&logo=shield" alt="Zero Root">
</p>

---

## 💡 What is OpenCode Agent?

Unlike toy chatbot wrappers that just spit out Markdown text you cannot execute, **OpenCode Agent** brings a complete desktop-grade developer workspace to Android.

It bundles the official **OpenCode arm64 Linux engine** inside an isolated **Ubuntu 24.04 glibc container** running entirely in Android user-space. Your agent can independently formulate execution plans, inspect project directories, write code in Monaco editor, execute bash commands & Python scripts, run test suites, and present interactive Git diffs before committing.

<p align="center">
  <a href="https://url.userdeep.com/oc-github-readme"><strong>👉 [Download on Google Play]</strong></a> &nbsp;|&nbsp; 
  <a href="https://opencode.userdeep.com/"><strong>🌐 [Official Documentation & Workspace Specs]</strong></a>
</p>

---

## ⚡ Six Superpowers in Your Pocket

### 1. 🛡️ Real Linux Engine (Zero Root Required)
Runs a true Ubuntu 24.04 arm64 glibc userspace container. Execute real `python3`, `bash`, `node` (v22), `git`, `curl`, `ripgrep`, and compile tools natively without rooting or unlocking your bootloader.

### 2. 🤖 Autonomous Coding & Git Diff Walkthrough
Ask the agent in natural language. It formulates plans, reads source files, makes precise edits, verifies with Bash commands, and displays an interactive Git diff walkthrough for every change.

### 3. 🧠 100+ Models or 100% Offline with Ollama
- **DeepSeek-R1 & V3**: Native live thinking token streaming.
- **Claude 3.7 Sonnet / 3.5 Sonnet & OpenAI GPT-4o / o1 / o3**.
- **Local Ollama**: Connect directly to your LAN or on-device Ollama instances with zero internet requirement.
- **Free Built-in OpenCode Zen Models**: Start coding immediately with 0 configuration and 0 API keys!

### 4. 💻 Pocket AI Server (PC Remote Drive & WebDAV)
Turn your phone into a low-power, quiet 24/7 AI server:
- **LAN Web UI**: Open Chrome or Safari on your laptop and drive your phone's full OpenCode interface over Wi-Fi.
- **Native WebDAV Mount**: Mount your phone’s project folder as a native network drive on Windows Explorer, macOS Finder, or Linux.
- **Cloudflare Argo Tunnel**: Instant secure remote access via QR code pairing.

### 5. 📂 Two-Way Android Storage Bridge (SAF)
Directly link your Android `Downloads`, `Documents`, or `Photos` folders with bidirectional background synchronization. Capture receipts or code screenshots with the camera directly into your workspace.

### 6. 🔋 24/7 Background Persistence & Anti-Kill Guard
Standard mobile AI apps get killed the second you switch apps or turn off your screen. OpenCode Agent runs a dedicated `SpecialUse` foreground service with notification tray protection, physical Wi-Fi network binding, and auto crash self-healing.

---

## 📊 Comparison: Why OpenCode Agent?

| Capability | Typical AI Chat Apps (ChatGPT / Claude) | Termux DIY Hack (CLI only) | **OpenCode Agent - AI** |
| :--- | :---: | :---: | :---: |
| **Real Code Execution** | ❌ Simulated | ⚠️ CLI only | **✅ Full Ubuntu 24.04 glibc** |
| **Monaco IDE & Git Diff UI** | ❌ Text box only | ❌ Vim / Nano CLI | **✅ Full Visual Editor & Diff Review** |
| **Phone Storage Sync (SAF)** | ❌ 1-by-1 manual upload | ⚠️ Fragile symlinks | **✅ Automatic 2-Way Sync** |
| **PC Browser & WebDAV Drive** | ❌ None | ⚠️ Complex scripts | **✅ 1-Click LAN Web & WebDAV Mount** |
| **100+ Models + Free Zen** | ❌ Vendor locked | ⚠️ Manual CLI setup | **✅ Any Provider + Free Zen Models** |
| **24/7 Anti-Kill Background** | ❌ Killed in seconds | ⚠️ Frequent OS battery kills | **✅ SpecialUse Foreground Service** |
| **Setup Time** | Instant | 2+ hours arcane setup | **✅ 1-Click Install, 0 Root** |

---

## 📦 Modular Runtime Tiers

All images are downloaded as incremental 7-Zip overlays with transparent size estimates:

- **Lite (~117 MB)**: Quick download. Ubuntu 24.04 base, OpenCode engine, Node.js 22, Git, vim, and OpenSSH.
- **Standard (~380 MB - Recommended)**: Full developer station. Adds Model Context Protocol (MCP) servers (Memory, Sequential-Thinking, Filesystem, GitHub) and Playwright headless API.
- **Full (~850 MB)**: Complete automation machine with real Chromium browser engine and computer-use tools.

---

## 🚀 Getting Started

### 1. Install via Google Play
Download the official release verified with Google Play Protect:  
👉 **[Get OpenCode Agent on Google Play](https://url.userdeep.com/oc-github-readme)**

### 2. Launch & Select Runtime Tier
Open the app, pick **Lite** or **Standard**, and let the app initialize your isolated Linux workspace.

### 3. Connect Models or Use Free Zen
Start chatting with the built-in free OpenCode Zen models immediately, or add your API keys under `Settings -> Providers` (DeepSeek, Anthropic, OpenAI, or local Ollama).

---

## 🌐 Links & Resources

- **Official Website**: [https://opencode.userdeep.com/](https://opencode.userdeep.com/)
- **Documentation**: [https://opencode.userdeep.com/features.html](https://opencode.userdeep.com/features.html)
- **Google Play Store**: [Install OpenCode Agent](https://url.userdeep.com/oc-github-readme)
- **Support & Feedback**: [contact@userdeep.com](mailto:contact@userdeep.com)

---

<p align="center">
  <sub>Developed with ❤️ by <a href="https://opencode.userdeep.com/">UserDeep</a>. Made for developers who build everywhere.</sub>
</p>
