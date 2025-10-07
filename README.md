# 🔰 Ultimate Matrix Anti-Cheat Config  
### by **PukarPlayz** | Version 3.0+

[![Matrix AntiCheat](https://img.shields.io/badge/Matrix-AntiCheat-blue.svg?style=for-the-badge)](https://www.spigotmc.org/resources/matrix-anti-cheat-advanced-cheat-detection-1-8-1-21.64635/)
[![Minecraft](https://img.shields.io/badge/Minecraft-1.8--1.21-green.svg?style=for-the-badge)]()
[![Author](https://img.shields.io/badge/Made%20by-PukarPlayz-orange.svg?style=for-the-badge)](https://github.com/PukarPlayz)

---

## ⚙️ About This Config
Hey everyone 👋  
This is fine-tuned **Matrix AntiCheat config**, built and tested over time on real PvP and competitive servers.  
It’s made to be **aggressive when needed**, **lightweight on performance**, and **smart enough** not to ruin legit gameplay.  

If you’re running a practice, combo, or network server and want solid cheat detection — this config will help you out.

---

## 🧩 Highlights
- ✅ Covers **every Matrix module**  
- ⚔️ Strong detection for **KillAura**, **Reach**, **Aimbot**, **Criticals**  
- 🧱 Handles **Scaffold**, **Tower**, and **FastPlace** exploits  
- 🛡️ Stops **Fly**, **NoSlow**, **Jesus**, **Velocity** movement cheats  
- 🧠 Detects **AutoArmor**, **AutoBot**, **AutoEat/Heal**  
- 🔔 Custom messages, **kicks**, and **tempbans** that actually make sense  
- 💬 Includes simple **anti-spam and chat moderation**  
- 🧩 Works perfectly on **Paper**, **Spigot**, and **Purpur** (1.8–1.21+)

---

## 🔨 Example Actions
Here’s how some of the punishments are set up:
```yaml
matrix msg %player% &c[WARNING] &eSuspicious activity detected. &7(Made by PukarPlayz)
matrix kick %player% &eUnauthorized Modifications Detected &7(Made by PukarPlayz)
matrix tempban %player% 1h &eRepeated Violations - 1 Hour Ban &7(Made by PukarPlayz)
````

Everything uses **VL (violation level)** logic — so players get fair warnings before being kicked or banned.

---

## 🧠 Why It’s Different

This isn’t just a default config with random tweaks.
Every value here was adjusted through testing with **real players**, including both **legit PvPers** and **cheat clients**, to find the right balance between accuracy and fairness.

* Fine-tuned for **Matrix v7+**
* Balanced **VL decay and weight**
* Focused on **PvP detection** while avoiding false positives
* Clean structure and clear comments for easy editing

---

## 📦 Installation

1. Download this repo or copy the `config.yml` file.
2. Drop it inside your Matrix plugin folder:

   ```
   /plugins/Matrix/config.yml
   ```
3. Reload Matrix with:

   ```
   /matrix reload
   ```
4. Done! You’re ready to test it out 🎮

---

## Author

Made with ❤️ by **[PukarPlayz](https://github.com/PukarPlayz)**
Version: **3.0+**

If this config helped you, don’t forget to leave a ⭐ on the repo — it really motivates me to keep improving it!
