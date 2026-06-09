# KOTOS

A Linux distribution focused on a polished, glass‑like desktop experience while remaining a practical daily driver.

## Overview
KOTOS is built on Kubuntu 26.04 LTS and uses KDE Plasma 6.6 (Wayland).  
The default theme – **Dark Glass** – combines a toned‑down glass effect with deep black backgrounds, ice blue accents and consistent skeuomorphic details.  
It is meant to be a comfortable replacement for Windows, not an exotic experiment.

## Features
- **Visual style**  
  - KWin effects: *Glass* with refraction, force blur and rounded corners.  
  - Application style: Kvantum (custom `KOTOS‑Black` theme).  
  - Icon theme: `Nova7` (glossy, 3D‑minimalist).  
  - Cursor theme: `Win7OS‑cursors`.  
  - SDDM login screen: customised `eucalyptus-drop` with a brand background.  
  - Plymouth boot screen: replaced with KOTOS logo.

- **Desktop layout**  
  - Bottom panel with autosize (fits content).  
  - Start menu: tiled layout (Windows 10/11 style).  
  - Task manager, system tray and digital clock on the panel.

- **Sound theme**  
  - `Glass paw` – based on Windows Vista Glass sounds, converted to OGG and integrated as a native sound theme.

- **Fonts**  
  - Interface: `Nunito` (clean, rounded sans).  
  - Monospace: `Maple Mono NF CN` (ligatures, CJK support).

- **Pre‑installed applications (full version)**  
  - Firefox (Flatpak), OnlyOffice, VLC, Telegram Desktop.  
  - **Zapret** – pre‑configured in the Russian build (anti‑censorship tool).

- **System requirements (full version)**  
  - CPU: 4 cores / 2.5 GHz (6 cores recommended for smooth glass effects).  
  - RAM: 4 GB (8 GB recommended).  
  - GPU: OpenGL 3.3 or newer.  
  - Disk: 25 GB (SSD strongly recommended).

## Download & Installation
The ISO image can be found in the **Releases** section of this repository (right sidebar).

1. Write the ISO to a USB drive (e.g. with `dd` or Rufus).  
2. Boot from the USB.  
3. Choose “Install KOTOS” and follow the installer.

For LiteKOTOS (lower hardware requirements, no glass effects) – see separate release notes.

## Building from source
The distribution is assembled with **Cubic** using the official Kubuntu 26.04 LTS ISO as a base.  
All custom themes, scripts and configuration files are stored in this repository.  

If you want to rebuild your own image, clone the repository and follow the instructions in `docs/build.md` (coming soon).

## License
KOTOS is a remix of free and open‑source software.  
Individual components are licensed under their respective licences (GPL, LGPL, CC‑BY‑NC‑ND for sound assets).  
The custom configuration scripts are released under the MIT licence.

---

*Created for users who appreciate a cohesive, glassy desktop without excessive hype.*
