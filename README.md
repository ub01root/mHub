# 🌌 mHub - The Ultimate HubCore Solution

![mHub Banner](https://img.shields.io/badge/Version-1.0.0--SNAPSHOT-blue?style=for-the-badge)
![Minecraft Support](https://img.shields.io/badge/Support-1.20.x--1.21.x-green?style=for-the-badge)
![Author](https://img.shields.io/badge/Author-AlexClient-cyan?style=for-the-badge)

**mHub** is a high-performance, lightweight, and extremely customizable HubCore designed for modern Minecraft networks. Built with efficiency in mind, it provides all the essential features to manage your lobby with a professional touch.

---

## 🚀 Key Features

*   **⚡ Advanced Server Selector**: 
    *   Support for **Custom Heads** (Base64/Value).
    *   Unique action system: `[MESSAGE]`, `[CONSOLE]`, `[PLAYER]`, `[CONNECT]`.
*   **🎮 Player Preferences**: 
    *   Toggle Scoreboard and Tablist visibility via GUI.
    *   Persistent storage (SQLite/MySQL).
*   **👁️ Dynamic Player Visibility**: 
    *   Hotbar item that changes material (Lime/Gray Dye) and name based on state.
*   **🛡️ CommandGuard**: 
    *   Strict Command Whitelist.
    *   **Total Tab-Complete Block**: Prevent players from seeing your plugins list.
*   **📊 Visuals**: 
    *   Animated Tablist & Scoreboard with **PlaceholderAPI** support.
    *   Custom **Chat Format** with HEX color support (`&#00D1FF`).
*   **⚔️ HubPvP**: 
    *   Enable/Disable PvP in the lobby with a single item.
*   **🔒 Lobby Protection**: 
    *   Disable block breaking, placing, hunger, damage, weather changes, etc.
*   **🚫 Anti World Downloader**: 
    *   Protect your builds from being stolen.
*   **🌍 Multi-Language**: 
    *   Full support for English (`en.yml`) and Spanish (`es.yml`).

---

## 🛠️ Actions System (Selector)

The server selector uses a powerful prefix system for its actions:

| Prefix | Description | Example |
| :--- | :--- | :--- |
| `[MESSAGE]` | Sends a colored message to the player | `[MESSAGE] &aConnecting...` |
| `[CONSOLE]` | Executes a command from console | `[CONSOLE] joinqueue %player% survival` |
| `[PLAYER]` | Executes a command as the player | `[PLAYER] spawn` |
| `[CONNECT]` | Connects to a Proxy server | `[CONNECT] survival` |

---

## 📜 Commands & Permissions

| Command | Description | Permission |
| :--- | :--- | :--- |
| `/mhub` | Shows plugin information | `None` |
| `/mhub reload` | Reloads all configuration files | `mhub.admin` |

*   **Bypass CommandGuard**: `op` players bypass all command and tab restrictions.
*   **AntiDownloader Alerts**: `mhub.notify.antidownloader`

---

## 📥 Installation

1.  Download the `mHub.jar` file.
2.  Place it in your server's `plugins` folder.
3.  Restart your server.
4.  Configure the files in the `/plugins/mHub/` directory.
5.  Enjoy your professional lobby!

---

## 🔗 Links

*   **Modrinth Profile**: [Visit AlexClient on Modrinth](https://modrinth.com/user/alexclient)
*   **Support**: For bugs or feature requests, please contact the author.

---

<p align="center">
  Developed with ❤️ by <b>AlexClient</b>
</p>
