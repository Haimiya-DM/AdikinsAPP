<div align="center">

# 🎬 Adikins
### The Ultimate Free Anime Streaming & Offline Player for Android

[![Android](https://img.shields.io/badge/Platform-Android_8.0+-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://android.com)
[![Kotlin](https://img.shields.io/badge/Language-Kotlin_1.9+-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)](https://kotlinlang.org)
[![Jetpack Compose](https://img.shields.io/badge/UI-Jetpack_Compose_M3-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)](https://developer.android.com/jetpack/compose)
[![Release](https://img.shields.io/github/v/release/your-username/Adikins?style=for-the-badge&color=8A2BE2)](https://github.com/Haimiya-DM/AdikinsAPP/releases/tag/Release)

<p align="center">
  <b>Adikins</b> is a fast, modern, and ad-free anime streaming application for Android built with Kotlin and Jetpack Compose Material 3. Stream in HD, customize subtitles down to the pixel, download episodes for offline viewing, and track your watch history with zero distractions.
</p>

[📥 Download Latest APK](https://github.com/Haimiya-DM/AdikinsAPP/releases/tag/Release) • [💬 Join Discord](https://discord.gg/UbrxstXrKcU) • [🌐 Official Website](https://your-website.pages.dev)

</div>

---

## ✨ Features

- **🚀 High-Speed HD Streaming**: Multi-server failover (Vidstreaming, MegaCloud, StreamWish) with automatic source resolution and adaptive bitrate streaming (HLS / m3u8).
- **🎨 Deep Subtitle Customization**:
  - Live subtitle preview canvas in Settings.
  - Custom font choices (Sans-Serif, Serif, Monospace, Cursive, Casual).
  - Configurable foreground font colors & opacity swatches.
  - Background box opacity (0% to 100%) and edge styles (Uniform Outline, Drop Shadow, Raised, Depressed).
  - Adjustable font sizing and vertical positioning.
- **📥 Offline Downloads**: Download episodes with real-time speed tracking, background notification progress, and low-storage safeguards.
- **📅 Airing Schedule & Calendar**: Stay updated with weekly release schedules grouped by day with exact broadcast times.
- **📚 Library & Watch History**:
  - Organize bookmarks into Watching, Completed, On Hold, and Plan to Watch.
  - Automatic progress resume (picks up exactly where you left off).
- **⚡ In-App OTA Update Engine**: Instant update notifications with changelog viewer and seamless one-tap in-app APK installer.
- **🔒 Privacy & Zero Ads**: No trackers, no popups, and no intrusive ads.

---

## 📱 Screenshots

<div align="center">
  <img src="screenshots/home.png" width="22%" />
  <img src="screenshots/detail.png" width="22%" />
  <img src="screenshots/player.png" width="22%" />
  <img src="screenshots/subtitles.png" width="22%" />
</div>

---

## 📥 Installation

1. Go to the [**Releases**](https://github.com/Haimiya-DM/AdikinsAPP/releases/tag/Release) page.
2. Download the latest `Adikins.apk` file.
3. Open the file on your Android device and tap **Install**.
   *(If prompted, allow "Install from unknown sources" for your browser or file manager).*
4. Enjoy streaming! Future updates will be notified and installable directly inside the app.

---

## 🛠️ Tech Stack & Architecture

- **Language**: 100% Kotlin
- **UI Framework**: Jetpack Compose with Material Design 3 (M3)
- **Architecture**: Clean MVVM (Model-View-ViewModel) + StateFlow coroutine pipelines
- **Media Engine**: ExoPlayer (Media3) with customized HLS / DASH stream support
- **Local Persistence**: Room SQLite Database + DataStore Preferences

---

