<p align="center">
  <img src="docs/assets/banner.png" alt="Ra1n Plugins Pack Banner" width="100%">
</p>

<h1 align="center">Ra1n Plugins Pack</h1>

<p align="center">
  <b>Custom Minecraft plugins for Paper 1.21+</b><br>
  Yellow themed • Simplified • Custom branded • No license key • No DRM
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Minecraft-Paper%201.21%2B-F4C542?style=for-the-badge" alt="Minecraft">
  <img src="https://img.shields.io/badge/Java-21-FF8C42?style=for-the-badge" alt="Java 21">
  <img src="https://img.shields.io/badge/Build-Gradle-4CAF50?style=for-the-badge" alt="Gradle">
  <img src="https://img.shields.io/badge/Status-Active-FFD95A?style=for-the-badge" alt="Status">
  <img src="https://img.shields.io/badge/Platform-Paper%20API-1E1E1E?style=for-the-badge" alt="Paper API">
</p>

---

## Overview

**Ra1n Plugins Pack** is a custom plugin collection for **Paper 1.21+** Minecraft servers, made by **xxenn / ra1nzao**.

This repository contains custom server plugins designed to be:

- easier to use
- easier to manage
- visually cleaner
- yellow themed
- custom branded
- free from forced license systems and DRM

The pack currently includes:

- **Ra1nCore** → a utility/core plugin
- **Ra1nOrder** → a custom order system plugin

---

## Included Plugins

| Plugin | Type | Main Purpose |
|--------|------|--------------|
| **Ra1nCore** | Utility / Core | Server management, teleportation, economy, GUI tools, admin utilities |
| **Ra1nOrder** | Order System | Public/player/admin orders, delivery flow, collect GUI, search/sort/filter |

---

## Why This Pack

This pack was made to provide a cleaner alternative to overly complicated server plugin setups.

### Main goals
- simple commands
- nice GUI-based systems
- modern Paper support
- custom yellow themed style
- easy plugin management
- custom branding by **xxenn / ra1nzao**
- **no license key system**
- **no DRM**

---

## Plugin Details

# Ra1nCore

**Ra1nCore** is the main utility/core plugin of the pack.

### Main features
- spawn system
- homes
- warps
- teleport requests
- teleport toggles
- auto teleport accept
- random teleport
- fly command
- economy system
- shop
- sell system
- sell history
- worth command
- crates
- team system
- stats
- leaderboard
- combat tools
- clearlag
- portals
- phantom controls
- player tracker
- spawner tools
- item control
- mythic-style tools
- admin GUIs
- yellow themed inventories and messages

### Highlights
- large utility set
- custom branding
- admin friendly
- simple usage
- Paper 1.21+ ready

---

# Ra1nOrder

**Ra1nOrder** is a custom order plugin for item orders and deliveries.

### Main features
- public orders GUI
- personal orders GUI
- admin orders GUI
- create orders from held items
- item delivery system
- collect stored items
- collect GUI
- order search
- order filters
- sorting
- pagination
- order expiry
- admin controls
- admin stats
- order logs
- webhook support
- price suggestions
- yellow themed inventories and messages

### Highlights
- designed for order-based gameplay
- clear player flow
- admin tools included
- webhook-ready
- no licensing system

---

## Screenshots

Add your screenshots to this folder:

```text
docs/screenshots/
```

Then show them here.

### Example
```md
## Screenshots

### Ra1nCore
<p align="center">
  <img src="docs/screenshots/raincore-main.png" alt="Ra1nCore Main GUI" width="80%">
</p>

### Ra1nOrder
<p align="center">
  <img src="docs/screenshots/rainorder-main.png" alt="Ra1nOrder Main GUI" width="80%">
</p>
```

### Suggested screenshots
- `Ra1nCore` main GUI
- `Ra1nCore` admin GUI
- `Ra1nOrder` public orders GUI
- `Ra1nOrder` personal orders GUI
- `Ra1nOrder` admin orders GUI

---

## Requirements

Before building or using the plugins, make sure you have:

- **Paper 1.21+**
- **Java 21**
- **Gradle** (or use `gradlew.bat`)
- **Vault** for optional economy features

---

## Repository Structure

```text
Ra1nCore/
Ra1nOrder/
docs/
  assets/
  screenshots/
README.md
.gitignore
```

### Suggested usage
- keep **each plugin in its own folder**
- keep screenshots and banners in `docs/`
- keep build output out of GitHub

---

## Build Instructions

Each plugin is a separate **Gradle** project.

### Build Ra1nCore
```bat
cd Ra1nCore
gradlew.bat build
```

### Build Ra1nOrder
```bat
cd Ra1nOrder
gradlew.bat build
```

### Built jar location
```text
build/libs/
```

---

## Installation

1. Stop your Minecraft server
2. Build the plugin you want
3. Take the generated `.jar` from `build/libs/`
4. Put the `.jar` into your server `plugins/` folder
5. Start the server
6. Check console for startup logs and errors

---

## Migration Notes

If you are replacing older plugins:

- back up old jars first
- back up old plugin data folders
- remove the old jar only after the new one is ready
- keep backups until the new plugin works correctly

For `Ra1nOrder`, you can also keep a migration checklist in the repo, for example:

```text
Ra1nOrder/MIGRATION-CHECKLIST.txt
```

---

## Branding

This plugin pack is custom branded as:

- **Ra1nCore**
- **Ra1nOrder**
- **Ra1n Plugins Pack**

### Creator
- **xxenn / ra1nzao**

### Discord
- **m1rel / xannaxxq**

### Branding style
- yellow themed GUIs/messages
- custom names
- custom startup text
- custom project structure
- custom release packaging

---

## Philosophy

This repository follows a simple idea:

> clean plugins, custom branding, easier usage, no forced licensing.

### Included principles
- no license key gate
- no DRM
- no forced premium locks
- easier to understand commands
- cleaner structure
- server-owner friendly design

---

## Publishing Tips

Good files to upload:
- `src/`
- `build.gradle`
- `settings.gradle`
- `gradlew.bat`
- `README.md`
- release notes
- command docs
- screenshots
- assets/banner

Do **not** upload:
- `build/`
- `.gradle/`
- `.gradle-bootstrap/`
- temp files
- local IDE folders
- old backups

---

## Roadmap

Possible future improvements:
- more GUI polish
- more modules
- more admin utilities
- more screenshot docs
- more release packaging polish
- more optimization / cleanup passes

---

## Support

For questions, updates, or feedback:

- use **GitHub Issues**
- contact on Discord: **m1rel / xannaxxq**

---

## Author

**xxenn / ra1nzao**  
Discord: **m1rel / xannaxxq**

---

## License

Add your preferred license here.

Examples:
- **All Rights Reserved**
- **Custom Private License**
- **MIT**
- **GPL**
- any other license you want to use

If you do not want others to freely reuse it, do **not** leave this section empty.

Example placeholder:

```text
Copyright (c) xxenn / ra1nzao.
All rights reserved.
```

---

## Footer

<p align="center">
  <b>Ra1n Plugins Pack</b><br>
  Custom Paper 1.21+ Minecraft plugins by <b>xxenn / ra1nzao</b><br>
  Yellow themed • Simplified • No license key • No DRM
</p>
