<p align="center">
  <img src="assets/banner.png" alt="Arus! Download Manager" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/baharida/arus-download-manager/releases/latest"><img src="https://img.shields.io/github/v/release/baharida/arus-download-manager?style=flat-square&color=13795B&label=Latest%20Release" alt="Latest Release" /></a>
  <img src="https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011%20(x64)-0F6E52?style=flat-square" alt="Windows 10/11 x64" />
  <img src="https://img.shields.io/badge/Installer-Full%20Offline-178766?style=flat-square" alt="Full Offline Installer" />
  <a href="https://chromewebstore.google.com/detail/mdidagnhjbilkgbafhchnghoflbakfmk"><img src="https://img.shields.io/badge/Chrome%20Web%20Store-Manifest%20V3-1E6B52?style=flat-square" alt="Chrome Web Store Extension" /></a>
  <a href="https://addons.mozilla.org/firefox/addon/arus-download-manager/"><img src="https://img.shields.io/badge/Firefox%20Add--ons-Manifest%20V3-FF7139?style=flat-square" alt="Firefox Add-ons Extension" /></a>
  <a href="https://github.com/baharida/arus-download-manager/releases/latest"><img src="https://img.shields.io/github/downloads/baharida/arus-download-manager/total?style=flat-square&color=0D9488&label=Downloads" alt="Total Downloads" /></a>
</p>

<p align="center">
  <strong>Arus! Download Manager</strong> is a fast, clean, native download manager for Windows (64-bit) combining dynamic multi-segment HTTP/HTTPS acceleration, native cloud decryption, a 65+ platform video/audio &amp; carousel downloader, offline FFmpeg creator tools, zero-data local Wi-Fi QR phone transfers, BitTorrent/Magnet support, and official <strong>Chromium</strong> &amp; <strong>Firefox</strong> browser extensions in one self-contained offline package.
</p>

<p align="center">
  <a href="https://github.com/baharida/arus-download-manager/releases/latest"><img src="https://img.shields.io/badge/Download%20for%20Windows%20(x64)-13795B?style=for-the-badge" height="38" alt="Download Arus! for Windows (64-bit)" /></a>&nbsp;&nbsp;<a href="https://chromewebstore.google.com/detail/mdidagnhjbilkgbafhchnghoflbakfmk"><img src="https://img.shields.io/badge/Chrome%20%2F%20Edge%20%2F%20Brave-242C38?style=for-the-badge" height="38" alt="Chrome Web Store Extension" /></a>&nbsp;&nbsp;<a href="https://addons.mozilla.org/firefox/addon/arus-download-manager/"><img src="https://img.shields.io/badge/Firefox%20%2F%20Zen%20%2F%20Floorp-FF7139?style=for-the-badge" height="38" alt="Mozilla Firefox Add-ons Extension" /></a>
</p>

---

## Interface Preview

Supports crisp **Light** and **Dark** themes, built-in **English** and **Indonesian** localization synced automatically with the browser extension, and an interactive quick-reference Feature Guide (`F1`).

### Light Mode
<p align="center">
  <img src="assets/preview-light.png" alt="Arus! Download Manager - Light Mode" width="100%" />
</p>

### Dark Mode
<p align="center">
  <img src="assets/preview-dark.png" alt="Arus! Download Manager - Dark Mode" width="100%" />
</p>

---

## Key Capabilities

### 1. Download Engine, Multi-Mirror & Cloud Decryption

| Capability | Description |
|---|---|
| **Dynamic 16-Segment Acceleration** | Splits HTTP/HTTPS downloads into up to 16 parallel connections with *dynamic work-stealing* (early-finishing segments automatically bisect the largest remaining chunk) and a live transfer speed graph. |
| **Multi-Mirror Booster** | Pulls a single large file simultaneously across multiple backup mirror URLs with `Content-Range` size verification and automatic per-segment failover if any mirror throttles or fails. |
| **Native MEGA.nz & Smart Cloud Resolver** | Built-in multi-segment `AES-128-CTR` decryption for public **MEGA.nz** files and folders, plus automatic direct-binary extraction for **Google Drive** (including >100 MB files), **MediaFire**, **OneDrive (`1drv.ms`)**, **WeTransfer (`we.tl`)**, **Dropbox**, **Pixeldrain**, **GoFile**, **Buzzheavier**, **KrakenFiles**, **Workupload**, **Internet Archive**, **Hugging Face**, **GitHub Releases**, **SourceForge**, **Wikimedia**, and **arXiv**. |
| **Stall Recovery & Expired Link Refresh** | Detects stalled sockets, auto-resumes upon Wi-Fi/ISP reconnection, prevents Windows from sleeping during active transfers, and lets you refresh expired temporary links (`HTTP 403` / `410`) without restarting from 0%. |
| **1-Click Bandwidth Saver (`🐢 Saver`)** | Instant speed-cap toggle accessible directly inside active **progress windows**, the main status bar, and the System Tray to keep video calls and online gaming lag-free, paired with an optional **Daily Data Cap (GB/day)**. |
| **BitTorrent, Magnet & Selective File Picker** | Full `.torrent` and `magnet:?` client with **per-file selection before downloading**, live DHT/peer metadata resolution, configurable seed duration/upload limits, and System / `HTTP` / `SOCKS5` proxy support secured via Windows DPAPI. |

### 2. 65+ Video, Audio & Social Gallery Downloader + Creator Tools

| Capability | Description |
|---|---|
| **65+ Social, Video & Creator Platforms** | Download up to 4K videos, playlists, audio tracks, and uncompressed original-resolution photo/video carousels from **YouTube**, **TikTok** (videos & `/photo/` slideshows), **Instagram** (Reels, mixed video+photo Carousels, Stories), **X/Twitter**, **Facebook**, **Threads**, **Pinterest**, **Telegram**, **Reddit**, **LinkedIn**, **Bluesky**, **Snapchat**, **Tumblr**, **Bilibili**, **Vimeo**, **Twitch**, **Kick**, **Pixiv**, **DeviantArt**, **ArtStation**, **Behance**, **Dribbble**, **SoundCloud**, **Bandcamp**, **Suno**, **Udio**, **Civitai**, and dozens more. |
| **Editor-Ready H.264 & Lossless Subtitle Muxing** | On-demand right-click conversion to **Editor-Ready MP4 H.264** (`yuv420p` + AAC for smooth timelines in Premiere Pro, DaVinci Resolve, & CapCut), **Compact WhatsApp MP4**, **320 kbps MP3** (with embedded cover art & ID3 tags), **Animated GIF**, and sub-second lossless **`.srt` / `.vtt` soft-subtitle embedding**. |
| **On-Demand Carousel-to-PDF Merger** | Combine downloaded educational or manga carousel images into a single aspect-ratio-preserving `.pdf` on demand—strictly manual so normal image downloads stay fast and untouched. |
| **HLS/DASH Stream Muxer & Clip Trimmer** | Automatically downloads and muxes segmented `.m3u8` / `.mpd` video manifests into clean playable `.mp4` files, or trims exact timestamp ranges (`mm:ss`–`mm:ss`) and **YouTube Chapters** prior to download. |

### 3. Local Wi-Fi Phone Share, File Management & Automation

| Capability | Description |
|---|---|
| **Send to Phone via Local Wi-Fi QR** | Transfer completed files directly to Android or iOS over your local Wi-Fi network by scanning a crisp built-in vector QR code—**zero mobile data usage, zero cloud upload, and 100% original uncompressed quality**. |
| **Instant Copy File (`Ctrl+C`)** | Copies the actual file onto the Windows Clipboard straight from the completion dialog or download table so you can paste (`Ctrl+V`) directly into WhatsApp Desktop, Telegram, Discord, Word, or Figma without opening File Explorer. |
| **Unified Batch Progress Window** | Multi-slide carousels and grouped downloads run cleanly inside a single consolidated progress window with combined speed charts and Windows Taskbar progress—zero pop-up spam. |
| **Page Link & Repository Grabber (`Ctrl+G`)** | Scans any webpage, public **MEGA.nz** folder, **GitHub Release**, **Hugging Face** model/dataset repo, or **Archive.org** item to filter and batch-download multiple files at once. |
| **Archive Extractor, Disk Relocation & Tidy List** | 1-click extraction for `.zip`, `.rar`, `.7z`, and `.tar.gz` archives, cross-volume `.aruspart` relocation when a target drive runs out of space, and 1-click cleanup of moved/deleted history entries. |
| **Smart Folder Rules, Scheduler & Backup** | Route save locations automatically by domain or file extension, schedule off-peak queue start/stop times, trigger automatic PC *Sleep*/*Shutdown* when finished, and export/import full JSON backups. |

### 4. Cross-Browser Extensions, Security & Integrity

| Capability | Description |
|---|---|
| **Official Chrome & Firefox Extensions (MV3)** | Available on the **[Chrome Web Store](https://chromewebstore.google.com/detail/mdidagnhjbilkgbafhchnghoflbakfmk)** (Chrome, Edge, Brave, Opera, Vivaldi) and **[Mozilla Add-ons](https://addons.mozilla.org/firefox/addon/arus-download-manager/)** (Firefox, Zen Browser, Floorp, Waterfox, LibreWolf) — featuring smart file interception, floating video & mixed-carousel pills, and right-click high-res image extraction through transparent page overlays. |
| **Windows Defender Auto-Scan** | Automatically scans completed downloads using the local **Windows Defender** engine (including archive contents) and applies standard NTFS *Mark-of-the-Web* (`Zone.Identifier`) attributes. |
| **Checksum Verifier & Verified Auto-Updater** | Built-in `SHA-256` and `MD5` hash verification, plus an in-app updater that enforces cryptographic `SHA-256` integrity checks before launching any update package. |

---

## Installation

1. Visit the **[Latest Release](https://github.com/baharida/arus-download-manager/releases/latest)** page.
2. Download **`Arus-Setup-x.y.z.exe`** (*Full Offline Installer* — includes the `.NET 10` x64 runtime, `yt-dlp`, `ffmpeg`, `aria2c`, and extension backup assets).
   *Note: `Arus-Update-x.y.z.exe` is the lightweight patch package used automatically by the built-in updater (`Help -> Check for Updates`).*
3. Run the installer and follow the setup wizard.
4. Install the companion browser extension for your browser:
   - **Google Chrome, Microsoft Edge, Brave, Opera, Vivaldi:** Install from the **[Chrome Web Store](https://chromewebstore.google.com/detail/mdidagnhjbilkgbafhchnghoflbakfmk)**.
   - **Mozilla Firefox, Zen Browser, Floorp, Waterfox, LibreWolf:** Install from **[Mozilla Firefox Add-ons](https://addons.mozilla.org/firefox/addon/arus-download-manager/)**.

> **Windows SmartScreen Note:** If Windows displays *"Windows protected your PC"* when launching the installer, click **More info** → **Run anyway**. This prompt appears for independently published freeware distributed without a paid Extended Validation (EV) code-signing certificate. Every release includes **`checksums.txt`** (`SHA-256`) so you can verify package authenticity.

---

## Architecture & Privacy

- **Isolated Local Loopback Bridge:** Communication between the browser extension (`chrome-extension://` and `moz-extension://`) and the desktop app runs strictly over local loopback (`127.0.0.1`), validating extension origins and rejecting external webpage requests (*anti-CSRF & anti-DNS rebinding*).
- **Zero Telemetry & Zero Ads:** Everything runs locally on your machine—no analytics, no download history tracking, no ads, and no third-party relay servers.
- **Encrypted Local Credentials:** Sensitive configuration values such as proxy passwords are encrypted at rest using the *Windows Data Protection API (DPAPI)* bound to your active Windows user account.

---

## Support the Project

**Arus! Download Manager** is independently built and completely **free—no ads, no feature paywalls, and no tracking**. If Arus! saves you time in your daily workflow, your support helps keep development and maintenance going strong:

<p align="center">
  <a href="https://ko-fi.com/baharida"><img src="https://img.shields.io/badge/Ko--fi-Support%20on%20Ko--fi-FF5E5B?style=for-the-badge&logo=kofi&logoColor=white" height="36" alt="Support on Ko-fi" /></a>&nbsp;&nbsp;<a href="https://saweria.co/baharida"><img src="https://img.shields.io/badge/Saweria-QRIS%20(Indonesia)-D97706?style=for-the-badge" height="36" alt="Support via Saweria (Indonesia QRIS)" /></a>
</p>
