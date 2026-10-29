# GM Sentinel

**PC monitoring & disk intelligence for Windows. Read-only, private, no account.**

[![Latest release](https://img.shields.io/github/v/release/Biggan2003/GM-SENTINEL-Releases?label=download&color=0a84c6)](https://github.com/Biggan2003/GM-SENTINEL-Releases/releases/latest)
![Windows 10 / 11](https://img.shields.io/badge/Windows-10%20%7C%2011%20(64--bit)-555)
![Freeware](https://img.shields.io/badge/licence-freeware-6d5dfc)

GM Sentinel shows what your PC is doing and where your disk space went, with live gauges,
heat-coloured charts and a full map of every folder and file. It **only reads**: it never
deletes, moves or changes your files.

## Download
**[⬇ Download the latest version](https://github.com/Biggan2003/GM-SENTINEL-Releases/releases/latest)**
and run `GM-Sentinel_<version>_x64-setup.exe`.

> Windows may show **"Windows protected your PC"** because the installer is new. Click
> **More info → Run anyway**. No administrator rights are needed.

## Features
- **Live monitoring:** CPU with real per-thread clocks, memory, GPU, disks, network, temperatures, battery.
- **Disk intelligence:** every folder and file, treemap, file types, largest items, growth history.
- **Fast Search:** instant search across all drives with filters for type, size, date and path.
- **Hardware details:** CPU, RAM slots (including empty ones), GPU and battery health.
- **Honest readings:** when Windows cannot report a value, the app says so. It never guesses.

## Updates
GM Sentinel checks this page once a day. When a new version is out, it shows the version number and
what changed, and installs **only when you click Update** (or automatically, if you choose that in
Settings). Every update is digitally signed; the app rejects anything that is not.

## Privacy & safety
- Works fully offline. No account, no telemetry, no personal data collected.
- The only automatic connection is the daily update check against this page.
- Read-only by design: no deleting, cleaning or "optimizing", no drivers, no admin rights.

## Verify your download (optional)
Each release includes `SHA256SUMS.txt`. In PowerShell:
```powershell
Get-FileHash .\GM-Sentinel_<version>_x64-setup.exe -Algorithm SHA256
```
The hash must match the one in `SHA256SUMS.txt`.

## System requirements
64-bit Windows 10 or 11 · about 15 MB disk space · WebView2 (installed automatically if missing).

## Feedback
Found a bug or have an idea? Open an [issue](https://github.com/Biggan2003/GM-SENTINEL-Releases/issues).

## Developer
**G. M. Biggan**, Applied AI Engineer ·
[LinkedIn](https://www.linkedin.com/in/g-m-biggan-371956305/) ·
[YouTube](https://www.youtube.com/@G.M-Biggan/videos)

---
© 2026 G. M. Biggan. All rights reserved. GM Sentinel is free for personal use; see the licence
agreement shown during installation. This repository hosts release builds only.
