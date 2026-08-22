# The Red Balloon — Releases

This repository contains the official macOS releases of **The Red Balloon**, a short atmospheric 2D journey through a fading illustrated world.

## Download

Download the newest `The-Red-Balloon-macOS-arm64.zip` from the [latest release](https://github.com/hanifb1360/the-red-balloon-releases/releases/latest).

The current build supports Apple Silicon Macs running macOS 12 or newer. It is self-contained, so .NET and MonoGame do not need to be installed.

## Install

1. Download and unzip `The-Red-Balloon-macOS-arm64.zip`.
2. Drag **The Red Balloon.app** into Applications.
3. Because the app is distributed independently and is not yet notarized, Control-click it the first time, choose **Open**, then confirm **Open**.

## Verify the download

Every release includes a `.sha256` checksum. In Terminal, run:

```bash
shasum -a 256 -c The-Red-Balloon-macOS-arm64.sha256
```

## Controls

| Action | Key |
| --- | --- |
| Walk | `A` / `D` or arrow keys |
| Jump | `Space` |
| Interact | `E` |
| Pause | `Esc` |
| Fullscreen | `F11` or `Option` + `Enter` |

Copyright © 2026 Hanif Bahari. All rights reserved.
