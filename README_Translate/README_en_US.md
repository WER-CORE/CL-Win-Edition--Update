<div align="center">

# Clegendary Launcher

**Ukrainian launcher for Minecraft: Java Edition**

[![Latest Release](https://img.shields.io/github/v/release/WER-CORE/CL-Win-Edition--Update?label=Latest_Release&style=flat-square)](https://github.com/WER-CORE/CL-Win-Edition--Update/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/WER-CORE/CL-Win-Edition--Update/total?label=Downloads&style=flat-square)](https://github.com/WER-CORE/CL-Win-Edition--Update/releases)
[![Made in Ukraine](https://img.shields.io/badge/Made_in-Ukraine-0057b7?style=flat-square)](https://github.com/WER-CORE/CL-OpenSource)

[**Official Website**](https://cl-launcher.app/) · [**Documentation**](https://wiki.cl-launcher.app/) · [**Download**](https://github.com/WER-CORE/CL-Win-Edition--Update/releases/latest) · [Source Code](https://github.com/WER-CORE/CL-OpenSource) · [Report an Issue](https://github.com/WER-CORE/CL-OpenSource/issues) · [Discord](https://discord.gg/RhyZjACs2U)

**README Languages:** [Українська](../README.md) · [English](README_en_US.md)  
Other translations: [contribute on Crowdin](https://uk.crowdin.com/project/clegendary-launcher)

</div>

---

> [!NOTE]
> This is the **releases and updates** repository for Clegendary Launcher. Source code and developer documentation are hosted in [CL-OpenSource](https://github.com/WER-CORE/CL-OpenSource).

## About

**Clegendary Launcher (CL)** is an open-source Ukrainian launcher for Minecraft: Java Edition. It brings game launching, version management, and mod management together in one interface.

We are building Ukrainian software and aiming to make it clean and reliable for everyday use.

## Features

- **Minecraft versions.** Install and launch supported versions of the game.
- **Historical versions.** Pre-Classic, Classic, Indev, Infdev, Alpha, and Beta via [BetaCraft](https://betacraft.uk/) integration. Compatibility of individual builds depends on your OS and Java environment.
- **Mods and content.** Search and install content from [Modrinth](https://modrinth.com/) and [CurseForge](https://www.curseforge.com/minecraft).
- **Mod loaders.** Support for multiple ecosystems including Forge, Fabric, Quilt, and NeoForge; loader availability depends on the game version.
- **Authentication.** Sign in using supported methods, including Microsoft Account and LittleSkin.
- **Settings.** Launch options, appearance customization, and management of installed instances.

## Interface

<div align="center">
<img width="750" alt="Clegendary Launcher interface — screenshot 1" src="https://github.com/user-attachments/assets/4f4696dd-031d-4d5f-b564-2b5225a62ace" />
<img width="750" alt="Clegendary Launcher interface — screenshot 2" src="https://github.com/user-attachments/assets/6d77eea0-c810-4a59-a42f-980b633d2ff1" />

  <sub>Archived screenshots from version 1.0.0.6R. The interface of recent releases may differ.</sub>
</div>

## Download and Installation

1. Open the [official website](https://cl-launcher.app/) or the [latest release](https://github.com/WER-CORE/CL-Win-Edition--Update/releases/latest) page.
2. Review the release notes and the list of available files.
3. Download the build for your operating system (all official builds are self-contained — no separate .NET Runtime installation is required).
4. Install or extract the launcher following the release instructions.

### Linux (Flatpak Repository)

The recommended way to install on Linux (`x64`) is via CL's own GPG-signed Flatpak repository:

```bash
flatpak install --user -y https://wer-core.github.io/CL-OpenSource/cl.flatpakref
```

Updates from the connected repository are available via `flatpak update io.github.wer_core.cl-opensource` (automatic update installation depends on your system and software center settings).

As alternatives, **AppImage** (`x64` / `arm64`) and the standalone **`CLegendaryLauncher-x64.flatpak`** bundle for manual installation are also available on the releases page.

> [!IMPORTANT]
> **Download Security**
>
> Download Clegendary Launcher only from official sources:
> - [Official Clegendary Launcher Website](https://cl-launcher.app/)
> - [GitHub Releases](https://github.com/WER-CORE/CL-Win-Edition--Update/releases/latest)
>
> Because the launcher is not currently code-signed, Windows SmartScreen may show an unknown publisher warning.
>
> Before running the file, make sure it was downloaded from one of the official sources. If you have any doubts about its origin, do not run it.

## Compatibility

| Edition | Windows | Linux | macOS | Status |
|---|:---:|:---:|:---:|---|
| **CL Avalonia** | ✓ | ✓ | ✓ | Current cross-platform edition |
| **CL WPF** | ✓ | — | — | Legacy Windows-only edition |

Availability of individual features may vary across platforms. Support for a given operating system does not guarantee compatibility with every Minecraft version.

## Support and Feedback

Found a bug or have a suggestion? Open an [issue in the source repository](https://github.com/WER-CORE/CL-OpenSource/issues) or join the [Discord community](https://discord.gg/RhyZjACs2U). When reporting a bug, please include your CL version, operating system, and steps to reproduce.
Want to help with localization? Visit [Crowdin](https://uk.crowdin.com/project/clegendary-launcher).

## Credits and Licenses

Thanks to the authors of the libraries, services, and tools that power Clegendary Launcher, including the teams behind **Modrinth**, **CurseForge**, supported mod loaders, and the UI components and icons used in the app.

Special thanks to **[BetaCraft](https://betacraft.uk/)** ([GitHub](https://github.com/betacraftuk)) for preserving historical Minecraft versions, maintaining the metadata archive, and providing compatibility tools. BetaCraft integration made historical version support possible in CL. Clegendary Launcher is an independent project and is not affiliated with BetaCraft.

For details on third-party components and their licenses, see the [source repository](https://github.com/WER-CORE/CL-OpenSource) and accompanying project files.

## Legal Notice

Clegendary Launcher is not an official product of Mojang Studios or Microsoft and is not affiliated with them. Minecraft and related trademarks belong to their respective owners.

---

<div align="center">

**Свій до свого по своє. 🇺🇦**

If CL has been useful to you, consider supporting the project with a star on [GitHub](https://github.com/WER-CORE/CL-OpenSource).

</div>
