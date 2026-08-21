<div align="center">

# ⚡ LSPosed Remake

### The Xposed Framework, Reimagined

A modernized rebuild of the **LSPosed Framework** featuring a complete **Material 3** redesign and support up to **Android 16 (Baklava)**.

Maintained with ❤️ by **EzequielDevTeam**

[![Android](https://img.shields.io/badge/Android-8.1%20~%2016-3DDC84?logo=android&logoColor=white)](https://www.android.com)
[![API](https://img.shields.io/badge/API-27%20%2B-3DDC84?logo=android&logoColor=white)](#supported-versions)
[![Material 3](https://img.shields.io/badge/UI-Material%203-6750A4?logo=materialdesign&logoColor=white)](#highlights)
[![License](https://img.shields.io/badge/License-GPL--3.0-blue)](#license)
[![Platform](https://img.shields.io/badge/Magisk-Riru%20%7C%20Zygisk-black)](https://github.com/topjohnwu/Magisk)

</div>

---

## 📖 Introduction

> **LSPosed** is an ART hooking framework delivering consistent APIs with original Xposed, leveraging the [LSPlant](https://github.com/LSPosed/LSPlant) hooking engine.

This repository hosts a **community-driven remake** of LSPosed: refreshed with Material You design, updated toolchains, and compatibility carried forward to Android 16 — while keeping full credit to the original [LSPosed Contributors](https://github.com/LSPosed/LSPosed).

## ✨ Highlights

| | Feature | Description |
|---|---|---|
| 🎨 | **Material 3 UI** | Complete overhaul with dynamic colors & modern Material You styling |
| 📱 | **Android 16 Ready** | Target & compile SDK 36 (Baklava), modern native toolchains |
| 🧩 | **Dual API** | Ships as both Riru & Zygisk Magisk modules |
| 🔌 | **Xposed API** | Full compatibility with the classic XposedBridge API |
| 🛠️ | **Actively Maintained** | Kept alive by EzequielDevTeam |

## 📱 Supported Versions

| Android | API |
|---------|-----|
| 8.1 ~ 16 (Baklava) | 27 ~ 36 |

## 📲 Installation

1. Install [Magisk](https://github.com/topjohnwu/Magisk) (latest stable recommended)
2. Flash the **Riru** or **Zygisk** variant of the module zip in Magisk
3. Reboot your device
4. Open the **Manager** app and start hacking 😉

> 💡 Zygisk variant requires enabling *Zygisk* in Magisk settings.

## 🏗️ Building from Source

```bash
# Clone with submodules
git clone --recursive <this-repo-url>
cd LSPosed

# Build everything (manager APK + Magisk module zips)
./gradlew :app:assembleRelease :magisk-loader:assembleRelease
```

**Requirements:** JDK 17 · Android SDK (API 36) · NDK 27 · CMake 3.22+

Artifacts are generated under `app/build/outputs/apk/` and `magisk-loader/build/outputs/`.

## 🙏 Credits

This project stands on the shoulders of giants:

| Project | Role |
|---|---|
| [LSPosed](https://github.com/LSPosed/LSPosed) | Original project & code |
| [Magisk](https://github.com/topjohnwu/Magisk/) | Makes all of this possible |
| [Riru](https://github.com/RikkaApps/Riru) | Code injection into zygote process |
| [LSPlant](https://github.com/LSPosed/LSPlant) | Core ART hooking framework |
| [Dobby](https://github.com/jmpews/Dobby) | Inline hooking |
| [XposedBridge](https://github.com/rovo89/XposedBridge) | The OG Xposed framework APIs |
| [EdXposed](https://github.com/ElderDrivers/EdXposed) | Fork source |
| ~~[SandHook](https://github.com/ganyao114/SandHook/)~~ | ART hooking framework (deprecated) |
| ~~[YAHFA](https://github.com/rk700/YAHFA)~~ | Previous ART hooking framework |
| ~~[dexmaker](https://github.com/linkedin/dexmaker) / [dalvikdx](https://github.com/JakeWharton/dalvik-dx)~~ | YAHFA hooker class generation |

- **Remake & Maintenance:** EzequielDevTeam

## 📄 License

LSPosed is licensed under the **GNU General Public License v3 (GPL-3)**.

See [LICENSE](LICENSE) or visit [gnu.org/copyleft/gpl.html](http://www.gnu.org/copyleft/gpl.html).
