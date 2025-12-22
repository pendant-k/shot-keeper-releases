# ShotKeeper 📸

> **Tame your desktop chaos instantly.**

# Shot Keeper Demo
https://github.com/pendant-k/shot-keeper-releases/raw/main/feature_1.mp4

**ShotKeeper** is a macOS utility that automatically detects new screenshots and helps you instantly organize them into folders. Say goodbye to a cluttered desktop.

## ✨ Key Features

- **🚀 Instant Detection**: Automatically detects screenshots (including Korean filenames `스크린샷...` and date patterns `YYYY-MM-DD`).
- **📹 Screen Recording**: Supports `.mov` screen recordings.
- **⚡️ Quick Actions**: A non-intrusive popup lets you move files with a single click or hotkey.
- **⌨️ Smart Hotkeys**: Bind number keys (1-9) to your favorite folders for lightning-fast organizing.
- **🌍 Multi-language**: Fully localized in **English**, **Korean**, and **French**.
- **🎨 Modern UI**: Clean, dark-mode inspired design that feels like a native Mac app.

## 📥 Installation

**Note**: This is a beta release and is not yet signed by Apple.

1.  Download the latest `.dmg` from the [Releases Page](https://github.com/pendant-k/shot-keeper/releases).
2.  Open the `.dmg` and drag ShotKeeper to your **Applications** folder.
3.  **Important**: When opening for the first time, you might see a "Unidentified Developer" or "Damaged App" warning.

### 🛠️ How to Fix the "Damaged App" Error

If macOS blocks the app, you can manually clear the security flag:

1.  Open **Terminal**.
2.  Run the following command:

```bash
sudo xattr -cr /Applications/ShotKeeper.app
```

3.  Enter your password (it won't show while typing) and press Enter.
4.  Launch ShotKeeper normally.

## 🛠 Usage

1.  **Launch ShotKeeper**: The settings window will appear.
2.  **Add Folders**: Click the `+` button to add target folders (e.g., "Work", "Design", "Memes").
3.  **Take a Screenshot**: Use the standard macOS shortcut (`Cmd + Shift + 3` or `4`).
4.  **Organize**:
    - A popup appears near your cursor.
    - Click a folder icon OR press the corresponding number key (`1`, `2`, `3`...).
    - Done! The file is moved instantly.

> **Pro Tip**: For the fastest experience, disable the macOS "Floating Thumbnail".
> (`Cmd + Shift + 5` -> Options -> Uncheck "Show Floating Thumbnail")

## 🆕 Updates (v0.0.2)

- **🇰🇷 Korean Support**: Fixed detection for Korean filenames (NFC/NFD issues).
- **📅 Date Patterns**: Now supports `YYYY-MM-DD` date patterns.
- **🎥 Screen Recordings**: Added `.mov` support.
- **📚 Usage Guide**: Added comprehensive usage instructions.

[View full release notes](./release_note/v0.0.2.md)

## 📄 License

Copyright © 2025 Donghan Kim. All Rights Reserved.
