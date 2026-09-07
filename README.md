<div align="center">

<h1>✦ Lumi ✦</h1>

### A softer, more magical desktop.

Lumi is a free, native macOS app that turns your favorite GIFs and videos into beautiful animated wallpapers.

[![macOS 14+](https://img.shields.io/badge/macOS-14%2B-f5d0fe?style=for-the-badge&logo=apple&logoColor=4c1d95)](https://www.apple.com/macos/)
[![Swift](https://img.shields.io/badge/Swift-Native-fbcfe8?style=for-the-badge&logo=swift&logoColor=9d174d)](https://www.swift.org/)
[![Free](https://img.shields.io/badge/Forever-Free-e9d5ff?style=for-the-badge)](#privacy)

### [↓ Download Lumi for macOS](../../releases/latest)

</div>

---

## Make your desktop feel like yours

Lumi lives quietly in your menu bar and brings a little motion to your Mac without getting in the way. Import a cozy video, dreamy animation, favorite game scene, nature loop, or anything else you love—and let it play behind your desktop icons.

## Features

| | |
|---|---|
| 🎞️ **GIF and video wallpapers** | Import GIF, MP4, MOV, M4V, and other formats supported by macOS. |
| 🖥️ **Multiple displays** | Use one wallpaper everywhere or give each display its own look. |
| ✨ **Wallpaper library** | Keep wallpapers organized with thumbnails, favorites, and collections. |
| 🌸 **Beautiful scaling** | Choose Fill, Fit, Stretch, or Center for every wallpaper. |
| 🔀 **Automatic rotation** | Shuffle wallpapers or change them on a schedule. |
| 🔋 **Battery-friendly controls** | Pause on battery, Low Power Mode, screen lock, sleep, or fullscreen apps. |
| 🫧 **Native menu-bar app** | Control Lumi without keeping a large window or Dock icon open. |
| 🔒 **Private and local** | Your wallpaper files stay completely on your Mac. |

## Installation

1. Open the [latest Lumi release](../../releases/latest).
2. Download **`Lumi.dmg`** from the **Assets** section.
3. Open the downloaded DMG.
4. Drag **Lumi** into the **Applications** folder.
5. Open Lumi from Applications.

> **First-launch note:** Lumi is currently distributed without Apple notarization. If macOS blocks the first launch, right-click **Lumi** and choose **Open**. If necessary, use **System Settings → Privacy & Security → Open Anyway**. Never disable Gatekeeper globally.

## Using Lumi

1. Click the Lumi icon in your Mac's menu bar.
2. Select **Choose Wallpaper**.
3. Pick a GIF or video from Finder.
4. Lumi imports it into your local library and starts playing it behind your desktop icons.

From the menu-bar panel, you can pause playback, move between wallpapers, shuffle your library, or open Settings.

## Requirements

- macOS 14 Sonoma or newer
- Apple Silicon or Intel Mac
- A video format supported by macOS AVFoundation

HEVC/H.265 playback depends on the media and codec support available on your Mac.

## Build from source

Install Xcode 15 or newer, clone or download this repository, and run:

```bash
chmod +x scripts/*.sh
./scripts/build-dmg.sh
```

The finished installer will be created at:

```text
dist/LiveWallpaper.dmg
```

If your build script still uses the original filename, rename the finished file to `Lumi.dmg` before creating a GitHub release.

## Privacy

Lumi is completely local and includes:

- No accounts
- No subscription or premium tier
- No advertisements
- No analytics or telemetry
- No cloud uploads
- No tracking

Your media never leaves your Mac.

## Free forever

Lumi is a personal open-source project. Every included feature is available for free—there are no trials, locked tools, purchases, or recurring payments.

## Contributing

Bug reports, ideas, and thoughtful improvements are welcome. Open an issue before making a large change so the direction can be discussed first.

## License

Lumi is available under the [MIT License](LICENSE).

---

<div align="center">

Made with Swift, tiny sparkles, and a love for pretty desktops. ♡

</div>
