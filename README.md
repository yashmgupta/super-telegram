# 🎧 System Audio Recorder

<div align="center">

![System Audio Recorder](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

**A beautiful, zero-dependency web application to record system audio directly from your browser**

[Live Demo](#) • [Features](#features) • [Installation](#installation) • [Usage](#usage)

</div>

---

## ✨ Features

- 🎵 **System Audio Recording** - Capture audio from browser tabs, applications, or entire screen
- 🎙️ **Dual Source Recording** - Record system audio + microphone simultaneously
- 📊 **Real-time Audio Visualizer** - Beautiful frequency spectrum visualization
- ⏱️ **Precision Timer** - Track recording duration with millisecond accuracy
- ⏸️ **Pause/Resume** - Full control over your recording session
- 💾 **Multiple Format Support** - Export as WebM, WAV, OGG, or MP3
- 📱 **Responsive Design** - Works seamlessly on desktop and mobile devices
- 🎨 **Modern UI** - Glassmorphism design with smooth animations
- 🔒 **Privacy First** - All processing happens locally in your browser
- 📦 **Zero Dependencies** - Pure vanilla JavaScript, no external libraries

## 🚀 Quick Start

### Option 1: Direct Download

1. Download `index.html` from this repository
2. Open the file in a modern web browser (Chrome, Edge, Firefox recommended)
3. Click "Start Recording" and grant permissions
4. Start recording!

### Option 2: Clone Repository

```bash
git clone https://github.com/yashmgupta/system-audio-recorder.git
cd system-audio-recorder
# Open index.html in your browser or serve with a local server
```

### Option 3: Deploy to GitHub Pages

1. Fork this repository
2. Go to Settings > Pages
3. Select main branch as source
4. Your app will be live at `https://yourusername.github.io/system-audio-recorder`

## 📖 Usage

### Recording System Audio

1. **Start Recording**: Click the red record button (⏺)
2. **Select Source**: In the browser prompt:
   - Choose the **tab** you want to record from
   - Or select **entire screen** to capture all system audio
   - ⚠️ **Important**: Check "**Share audio**" or "**Share system audio**" checkbox
3. **Control Recording**:
   - ⏸️ Pause/Resume recording
   - ⏹️ Stop and save recording
4. **Download**: Your recording appears in the list below - click download (⬇)

### Recording Options

| Option | Description |
|--------|-------------|
| **Output Format** | WebM (default), WAV, OGG, or MP3 |
| **Audio Source** | System/Tab audio only or System + Microphone |
| **File Name** | Customize the output filename |

## 🎯 Use Cases

- 📚 **Education**: Record online lectures, webinars, or tutorials
- 🎮 **Gaming**: Capture game audio for streaming or editing
- 🎼 **Music**: Record web-based music production or DJ sessions
- 💼 **Professional**: Save important meetings, presentations, or calls
- 🎬 **Content Creation**: Extract audio from videos or create podcasts
- 🔊 **Audio Archiving**: Save streaming audio content

## 🛠️ Technical Details

### Browser Compatibility

| Browser | Support | Notes |
|---------|---------|-------|
| Chrome 94+ | ✅ Full | Recommended |
| Edge 94+ | ✅ Full | Recommended |
| Firefox 90+ | ✅ Full | May require "media.getdisplaymedia.audio.enabled" flag |
| Safari 13+ | ⚠️ Limited | No system audio capture support |
| Opera 80+ | ✅ Full | Chromium-based |

### Technologies Used

- **MediaDevices API** - Screen/audio capture via `getDisplayMedia()`
- **MediaRecorder API** - Audio recording and encoding
- **Web Audio API** - Real-time visualization and audio processing
- **Canvas API** - Audio frequency spectrum rendering
- **Blob API** - File handling and downloads

### Audio Formats

- **WebM** (Opus codec) - Best compression, widely supported
- **WAV** (PCM 16-bit) - Uncompressed, high quality, large files
- **OGG** (Vorbis/Opus) - Open format, good compression
- **MP3** - Converted from WAV (note: actual MP3 encoding requires additional libraries)

## ⚙️ Customization

The application is built with vanilla JavaScript and can be easily customized:

```javascript
// Change recording time slice
mediaRecorder.start(100); // milliseconds

// Modify visualizer FFT size
analyser.fftSize = 256; // Powers of 2: 128, 256, 512, 1024, 2048

// Adjust audio quality
const options = {
  audioBitsPerSecond: 128000 // 128 kbps
};
```

## 🔐 Privacy & Security

- ✅ All audio processing happens **locally** in your browser
- ✅ No data is sent to external servers
- ✅ Requires explicit user permission before recording
- ✅ Open-source code - fully auditable
- ✅ Works offline after initial page load

## 🐛 Troubleshooting

### "No audio track detected" Error

**Solution**: When prompted, make sure to check the "**Share audio**" or "**Share system audio**" checkbox in the browser's sharing dialog.

### Firefox: No audio in recording

**Solution**: Enable system audio capture:
1. Type `about:config` in address bar
2. Search for `media.getdisplaymedia.audio.enabled`
3. Set to `true`

### Safari: Cannot record system audio

**Issue**: Safari doesn't support system audio capture via `getDisplayMedia()`.

**Workaround**: Use Chrome, Edge, or Firefox for system audio recording.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 🌟 Acknowledgments

- Inspired by modern audio recording tools
- Built with ❤️ using Web APIs
- UI design influenced by glassmorphism trends

## 📞 Contact

**Yash Gupta** - [@yashmgupta](https://github.com/yashmgupta)

Project Link: [https://github.com/yashmgupta/system-audio-recorder](https://github.com/yashmgupta/system-audio-recorder)

---

<div align="center">

**If you found this useful, please consider giving it a ⭐ star!**

Made with 💜 by [Yash Gupta](https://github.com/yashmgupta)

</div>