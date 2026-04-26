# WatchAmp — Issue Tracker
<img width="512" height="512" alt="Designer-2" src="https://github.com/user-attachments/assets/5c73185d-84a6-4ccb-8d0a-84f99068759f" />

Issue tracker for SwiftUI App, WatchAmp for watchOS.

This repository is used **only** to track bugs, feature requests, and feedback for **WatchAmp**, a watchOS app built with **SwiftUI**.

🚫 **Source code is not shared in this repository.**

---

## About the App

WatchAmp is a watchOS app for browsing a Plex music library and playing music directly from Apple Watch.

The app authenticates with Plex, discovers reachable servers, loads music libraries, and plays tracks on-device using a watchOS audio session configured for long-form playback. The project is optimized around the practical constraints of watchOS audio:

- Bluetooth headphone routing is central to playback behavior
- direct streaming is preferred when it is reliable
- transcoding can be used to download a local playable file before playback

## Features

- Plex PIN-based authentication
- Plex server discovery and selection
- Music library browsing
- Artist, album, playlist, and search flows
- Now playing screen with transport controls
- Queue playback with next/previous support
- Offline/download cache support
- Progressive transcode download flow for difficult playback cases

---

## Screenshots

<p align="center">
  <img width="200" alt="incoming-228FF7BE-44FA-49D1-9EFA-AC620559F7B2" src="https://github.com/user-attachments/assets/44a73e5f-224b-4ab3-93e4-46346d727ddd" />
  <img width="200" alt="Simulator Screenshot - Apple Watch Series 11 (46mm) - 2026-04-06 at 18 12 23" src="https://github.com/user-attachments/assets/c17d2267-ea6f-4497-b7fd-c4a4838bb69b" />
   <img width="200" alt="Simulator Screenshot - Apple Watch Series 11 (46mm) - 2026-04-06 at 18 15 18" src="https://github.com/user-attachments/assets/e42b96c9-78c1-4101-a9bd-9367a90c5265" />
  <img width="200" alt="Simulator Screenshot - Apple Watch Series 11 (46mm) - 2026-04-06 at 18 13 46" src="https://github.com/user-attachments/assets/cade5995-39ab-4de8-985d-55e7ef974751" />
  <img width="200" alt="Simulator Screenshot - Apple Watch Series 11 (46mm) - 2026-04-06 at 18 14 15" src="https://github.com/user-attachments/assets/22d12f0c-e5f5-4fdd-9bac-073b2316261c" />
  <img width="200" alt="Simulator Screenshot - Apple Watch Series 11 (46mm) - 2026-04-06 at 18 14 27" src="https://github.com/user-attachments/assets/1106e2ea-d676-42fc-a6fc-6cfd67ac5809" />
 <img width="200" alt="Simulator Screenshot - Apple Watch Series 11 (46mm) - 2026-04-06 at 18 17 38" src="https://github.com/user-attachments/assets/3936e454-ac01-436f-935e-3f01a7ddade5" />
 <img width="200"alt="Simulator Screenshot - Apple Watch Series 11 (46mm) - 2026-04-06 at 18 16 23" src="https://github.com/user-attachments/assets/5b0d25d7-00ad-4ba1-b2b4-76dbb1a6a1ac" />
</p>

---

## How to Use This Repo

Please use **GitHub Issues** to:

- 🐞 Report bugs or crashes
- 💡 Suggest new features
- 📈 Make UX or accessibility suggestions

➡️ **Before opening a new issue**, please check if a similar one already exists.

---

## Include This Info in Bug Reports

When reporting a bug, please include:

- watch model (e.g. Apple Watch Series 9)
- Cellular or Wifi Only
- watchOS version
- App version
- Steps to reproduce
- Expected vs actual behavior
- Screenshots if possible

---

## TestFlight / App Store

- TestFlight: https://testflight.apple.com/join/eT4GWjY7

---

## Contact

For private or sensitive feedback:
- Email: testing@nerdypup.com

Thanks for helping improve **WatchAmp** 🙌
