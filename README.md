# 🎬 AI Video Editor - Flutter

A fast, lightweight & AI-powered video editor built with Flutter. Trim, cut, merge, add music & auto-subtitles in one app.

![Flutter](https://img.shields.io/badge/Flutter-3.19-blue?logo=flutter)
![Dart](https://img.shields.io/badge/Dart-3.3-blue?logo=dart)
![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20Linux-green)
![License](https://img.shields.io/badge/License-MIT-yellow)

### ✨ Demo
> Add your app screenshot/video link here
> `![App Demo](assets/demo.gif)`

---

### 🔥 Features

**Core Editing:**
- ✂️ Trim & Cut videos with frame accuracy
- 🔗 Merge multiple clips
- 🎵 Add background music & sound effects
- 🔤 Add text, stickers & overlays
- 🎨 Filters & Transitions (Fade, Slide)

**AI Features (Your USP for Viva):**
- 🤖 Auto-Subtitles using AI (Whisper / GROQ)
- 🗣️ Text-to-Speech Voiceover
- 🧠 AI Highlight Detection - Auto finds best moments

**Export:**
- 📤 Export in 720p / 1080p
- ⚡ Fast rendering
- 📱 Share directly to Instagram, YouTube

---

### 🛠️ Tech Stack

- **Framework:** Flutter 3.19+
- **Language:** Dart
- **Video Engine:** `ffmpeg_kit_flutter`, `video_editor`
- **AI:** GROQ API / Whisper for subtitles
- **State:** Provider / GetX

---

### 🚀 How to Run

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/ai-video-editor.git

# Go to folder
cd ai-video-editor

# Get packages
flutter pub get

# Run on Linux (your lab PC)
flutter run -d linux

# Run on Android
flutter run
