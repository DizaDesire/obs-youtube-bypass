# 🛠️ YouTube Safety Dock - OBS Plugin

<p align="center">
<img src="https://images.weserv.nl/?url=https://raw.githubusercontent.com/DizaDesire/obs-youtube-safety-dock/refs/heads/main/header.png" alt="YouTube Safety Dock" width="100%" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/license-MIT-red?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/github/stars/DizaDesire/obs-youtube-safety-dock?style=for-the-badge&color=orange" alt="Stars">
  <img src="https://img.shields.io/github/issues/DizaDesire/obs-youtube-safety-dock?style=for-the-badge&color=yellow" alt="Issues">
  <img src="https://img.shields.io/badge/OBS-Plugin-blueviolet?style=for-the-badge" alt="OBS Plugin">
</p>

<p align="center">
What is this for?
<br>
I developed this plugin/module to help with self-control and discipline when recording videos for YouTube. The issue is that YouTube has introduced new rules prohibiting profanity in the first 15 minutes of a video—which can be challenging—and this tool helps track the time until it is permissible to swear.
</p>

---

## ✨ Features

- ⏱️ **Authorization** — Automatic connection, just log in once and the plugin will automatically turn on when OBS starts
- 🖥️ **OBS Dock Panel** — Modularity, the plugin is developed in web format, which is why you don’t need to install anything, just add a direct link to the plugin in the dock panel and you can use it.
- ⚡ **Lightweight** — Doesn't load the system in any way, all plugin components are on the server, you don't sacrifice anything.

---

## 📥 Installation

1. Copy the link to the **plugin**.
2. Start OBS, click dock-panels -> custom dock-panels.
3. In the window that opens, insert a link to the plugin into the free input field and set a name for the dockpanel, for example “Timer”.
4. And click service -> settings websocket
5. Going to the websocket settings, click show connection information and copy the unique server password.
6. In the added dock panel, find the settings button and there in the IP and password input field, enter the password and click connect.
7. Enjoy, the timer will start automatically when you start recording or manually through the settings panel inside the plugin. The plugin is completely automatic, updates come automatically, you don’t need to do anything, your data is not transferred anywhere and is stored in the local session of the running OBS.

```
Dock panels → Custom dock → YouTube Safety Dock
```

## ⚙️ Requirements

- OBS Studio 31+
- Windows 10 / Windows 11 (64-bit)

---

## 👨‍💻 Developer

**Diza Desire**

GitHub: https://github.com/DizaDesire

---

## 📄 License

This project is licensed under the **MIT License**.

See the **LICENSE** file for details.

---

<p align="center">
Made with ❤️ for the OBS Studio community.
<br>
If this plugin is useful, consider leaving a ⭐ on GitHub!
</p>