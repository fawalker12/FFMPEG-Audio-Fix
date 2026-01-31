# FFMPEG-Audio-Fix (Aufix.py) — Termux Ready

A Python tool to fix audio-video delay and encode videos with subtitles using FFmpeg.  
This version is configured for **Android Termux** with full paths to avoid permission issues.

---

## ⚡ Features

- Fix audio delay in videos
- Encode video with subtitles

---

## 🛠 Requirements

- Android device  
- Termux- (Recommend to installed from [F-Droid - https://f-droid.org/packages/com.termux/ ])  
- Python
- FFmpeg

---

## ✅ Installation in Termux(One Time)

Open Termux and run:


```
# Update packages
pkg update && pkg upgrade -y

# Install Python
pkg install python -y

# Install FFmpeg
pkg install ffmpeg -y

# Optional: install git
pkg install git -y

# Clone the repo
git clone https://github.com/fawalker12/FFMPEG-Audio-Fix.git

```

##Usage
```
#Enter Repo
cd FFMPEG-Audio-Fix

#Run Program
python Aufix.py

```
