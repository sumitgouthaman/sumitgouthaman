## Hi there

I'm Sumit. I work on distributed systems by day. Lately I've been enjoying **vibe-coding** — building small, focused apps purely for my own use. Audience of one. No roadmap, no release notes, no users to please.

---

### Things I'm building

#### BusDash — Android & Wear OS Transit Dashboard

**[GitHub](https://github.com/sumitgouthaman/BusDash)**

A fast, glanceable transit dashboard for Android and Wear OS, powered by the OneBusAway API. Built for daily commuters who take the same bus from the same stops every day — optimized for that specific use case, not general transit browsing.

- **Real-time Arrivals**: Handles API rate limits gracefully with caching.
- **Location-aware**: Shows nearby stops automatically and floats starred stops to the top.
- **Starred Routes**: Star specific routes within a stop for a focused view.
- **Commute Notifications**: Schedule recurring alerts for typical commutes — get a push notification before departure showing the next buses, synced to Wear OS.
- **Map Integration**: Open any stop directly in Google Maps from the stop detail screen.
- **Wear OS Companion**: Syncs starred stops and settings from your phone.
- **Dark UI**: High-contrast, transit-themed dark mode throughout.

<div style="display: flex; gap: 10px; overflow-x: auto; padding: 10px 0; align-items: center;">
  <img src="https://raw.githubusercontent.com/sumitgouthaman/BusDash/main/screenshots/screenshot_phone.png" width="170">
  <img src="https://raw.githubusercontent.com/sumitgouthaman/BusDash/main/screenshots/recording_phone.gif" width="170">
  <img src="https://raw.githubusercontent.com/sumitgouthaman/BusDash/main/screenshots/screenshot_watch.png" width="115">
  <img src="https://raw.githubusercontent.com/sumitgouthaman/BusDash/main/screenshots/recording_watch.gif" width="115">
</div>

---

#### Habit Tracker — Web & Wear OS

**[Live](https://habit-tracker.sumitgouthaman.com)** · **[GitHub](https://github.com/sumitgouthaman/habit-tracker)**

A seamless cross-device habit tracker with a web PWA and a dedicated Wear OS companion app.

- **Smart Tracking**: Daily, weekly, and monthly habits with auto-reset.
- **Flexible Goals**: Track binary completion (Done/Not Done) or specific counts.
- **Rich Analytics**: Completion charts, streaks, day-of-week breakdowns, personal bests, and per-period value tracking.
- **Cloud Sync**: Sign in with Google for real-time multi-device sync via Firebase — or use Guest Mode with local storage.
- **Data Backup**: Export and import all habits and history as a JSON file.
- **Wear OS Companion**: Check off habits directly from your wrist (built with Jetpack Compose).
- **Offline Ready**: Works without an internet connection.

<div style="display: flex; gap: 10px; overflow-x: auto; padding: 10px 0;">
  <img src="https://raw.githubusercontent.com/sumitgouthaman/habit-tracker/main/screenshots/main_page.png" width="180">
  <img src="https://raw.githubusercontent.com/sumitgouthaman/habit-tracker/main/screenshots/stats.png" width="180">
  <img src="https://raw.githubusercontent.com/sumitgouthaman/habit-tracker/main/screenshots/stats_3.png" width="180">
  <img src="https://raw.githubusercontent.com/sumitgouthaman/habit-tracker/main/screenshots/settings.png" width="180">
</div>

**Wear OS App:**

<div style="display: flex; gap: 10px; padding: 10px 0;">
  <img src="https://raw.githubusercontent.com/sumitgouthaman/habit-tracker/main/android/screenshots/wearos_screenshot.png" width="120">
  <img src="https://raw.githubusercontent.com/sumitgouthaman/habit-tracker/main/android/screenshots/wearos_recording.gif" width="120">
</div>

---

#### pdf-cropper — Per-Page PDF Cropping

**[GitHub](https://github.com/sumitgouthaman/pdf-cropper)**

A locally-hosted web app for cropping individual pages of a PDF — each page independently. Most PDF tools apply the same crop rectangle to every page, which doesn't work well for scanned books or mixed-format PDFs. This tool was built to handle exactly that case.

- Crop each page independently, with a sidebar thumbnail preview.
- Runs locally — no cloud services, no uploads.

<div style="text-align: center;">
<img src="https://raw.githubusercontent.com/sumitgouthaman/pdf-cropper/main/screenshots/recording.gif" width="650">
</div>

---

#### Morse Code Trainer

**[Live](https://morse-code.sumitgouthaman.com)** · **[GitHub](https://github.com/sumitgouthaman/morse-code-trainer)**

An interactive web app for practicing morse code. Built using Gemini CLI and Q CLI as a rapid development experiment.

- Multiple practice modes (character ↔ morse, audio recognition)
- Learn mode for studying patterns
- Mobile-responsive with PWA support

<div style="text-align: center;">
<img src="https://raw.githubusercontent.com/sumitgouthaman/morse-code-trainer/main/_screenshots/local/mobile/combined.gif" width="280">
</div>

---

#### OBA macOS — Bus Arrivals in Your Menu Bar

**[GitHub](https://github.com/sumitgouthaman/oba-macos)**

A native macOS menu bar app that shows real-time bus arrivals for your saved stops via the OneBusAway API.

<div style="text-align: center;">
<img src="https://raw.githubusercontent.com/sumitgouthaman/oba-macos/main/screenshots/popover.png" width="300">
</div>

---

#### Podcast Smart Trim

**[GitHub](https://github.com/sumitgouthaman/podcast-smart-trim)**

A CLI tool that uses AI to automatically identify and remove advertisements from podcasts. Built as a way to test Antigravity, Google's new IDE.

- **AI Transcription**: Uses `openai-whisper` for accurate transcripts.
- **Smart Ad Detection**: Uses Google Gemini to analyze context and identify ad breaks.
- **Ad Removal**: Uses `ffmpeg` to remove the identified segments.

---

#### iPad Photo Frame

**[GitHub](https://github.com/sumitgouthaman/ipad-photo-frame)**

Turn an unused iPad into a digital photo frame — no cloud services, logins, or remote backends required. I wanted a simple way to repurpose an old iPad without relying on third-party services. The app exposes a local web server so you can drag and drop photos from any browser on your network. Inspired by a similar feature in VLC for iOS.

- **Fully Offline**: No cloud accounts required.
- **Wireless Uploads**: Drag and drop photos from any browser on your local network.
- **No Cables**: Add new photos without connecting to a computer.
- **Privacy First**: Photos stay on your device.
