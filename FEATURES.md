# Noizzz Features

### 🎛️ Core Processing Tools
1. **Volume Booster:**
   - Increase the audio volume of any video file up to 1000%.
   - Includes an built-in audio limiter to prevent severe distortion when boosting volume heavily.
2. **Music & Background Remover (Vocal Isolation):**
   - Uses advanced on-device AI (`Demucs` / `RNNoise`) to analyze the video's audio track.
   - Completely removes background music and isolates human vocals seamlessly.
3. **Video Merger:**
   - Select and combine multiple video files into a single, seamless video.
4. **Video Compressor:**
   - Reduce the file size of MP4 and WebM videos without sacrificing noticeable visual quality.
5. **Audio Remover (Mute Video):**
   - Instantly strip the audio track from any video, rendering it completely mute.

### 🔒 Privacy & Architecture
- **100% Local Processing:** Uses `ffmpeg.wasm` and local AI models to process all media directly on your device. No video or audio is ever uploaded to a cloud server, guaranteeing complete privacy.
- **Offline Capable:** Because everything runs locally, the app functions entirely offline once installed.
- **Cross-Platform Flexibility:**
  - **Windows Desktop:** Packaged as an `.exe` native application.
  - **Android:** Packaged as an `.apk` mobile application.
  - **Web:** Can run directly in modern web browsers.

### 🎨 User Experience & Interface
- **Dark/Light Mode:** Built-in theme toggling that saves your preference locally.
- **Smart Device Detection:** Automatically detects if you are on a mobile device and provides intelligent warnings (e.g., suggesting you switch to desktop for videos longer than 45 seconds or larger than 150MB to prevent browser throttling).
- **Wake Lock Support:** Prevents your device screen from sleeping or turning off while heavy video processing is actively running.
- **Real-Time Progress:** Shows percentage-based progress indicators during heavy AI operations (like separating vocals) or FFmpeg rendering.
