# 🧱 Minecraft Version Archive

A full archive of **every official Minecraft release**, from `1.0` to the latest version — with both `client.jar` and `server.jar` hosted directly in the [Releases tab](https://github.com/MagicDippyEgg/Minecraft-Version-Archive/releases).

> **This is an automated archive.** It updates itself every week and adds new versions when Mojang releases them.

---

## 📦 What’s Included?

For each release version:
- ✅ `client.jar` (used by the Minecraft Launcher)
- ✅ `server.jar` (used for hosting multiplayer servers — if available)

You can download them directly from the [Releases](https://github.com/MagicDippyEgg/Minecraft-Version-Archive/releases) page — no need to reverse engineer Mojang’s API or dig through launcher files.

---

## 🔄 How does this work?

This repository is powered by:

- 🐍 A Python script that fetches version data from Mojang’s official [version manifest](https://piston-meta.mojang.com/mc/game/version_manifest_v2.json)
- 🤖 A GitHub Actions workflow that:
  - Runs weekly (every Monday)
  - Checks if Mojang has released a new version
  - Downloads the latest `client.jar` and `server.jar`
  - Publishes them to a new GitHub Release

---

## 📜 License

This project only redistributes Mojang's publicly available `.jar` files for **archival and preservation** purposes.  
All Minecraft assets are © Mojang Studios / Microsoft. This project is not affiliated with or endorsed by Mojang.

---

## 💬 Credits

Maintained  by [@MagicDippyEgg](https://github.com/MagicDippyEgg).  
Inspired by the desire to make Minecraft history easily accessible.

