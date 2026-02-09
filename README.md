# 🎧 Super Telegram

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
git clone https://github.com/yashmgupta/super-telegram.git
cd super-telegram
# Open index.html in your browser or serve with a local server
```

### Option 3: Deploy to GitHub Pages

1. Fork this repository
2. Go to Settings > Pages
3. Select main branch as source
4. Your app will be live at `https://yourusername.github.io/super-telegram`

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
- 💼 **Professional**: Capture conference calls, meetings, or presentations
- 🎮 **Gaming**: Record game audio for streaming or content creation
- 🎵 **Music**: Capture online radio, streaming music, or audio from videos
- 🔧 **Technical**: Record system sounds for debugging or testing

## 🛠️ Technical Details

### Browser Compatibility

| Browser | System Audio | Microphone | Visualizer |
|---------|--------------|------------|------------|
| Chrome 94+ | ✅ | ✅ | ✅ |
| Edge 94+ | ✅ | ✅ | ✅ |
| Firefox 90+ | ✅ | ✅ | ✅ |
| Safari 15.4+ | ⚠️ Limited | ✅ | ✅ |
| Opera 80+ | ✅ | ✅ | ✅ |

### APIs Used

- **MediaDevices.getDisplayMedia()**: Captures screen/tab audio
- **MediaDevices.getUserMedia()**: Captures microphone input
- **MediaRecorder API**: Records audio streams
- **Web Audio API**: Provides real-time visualization
- **Blob API**: Handles audio data and downloads

## 📋 Requirements

- Modern web browser with support for:
  - MediaRecorder API
  - getDisplayMedia API
  - Web Audio API
- HTTPS connection (or localhost for development)
- Permissions for:
  - Screen/Tab sharing
  - Microphone access (optional)

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Built with vanilla JavaScript - no frameworks needed!
- Icons and badges from [Shields.io](https://shields.io)
- Inspired by the need for a simple, privacy-focused audio recording solution

## 📞 Support

If you encounter any issues or have questions:

- 🐛 [Open an issue](https://github.com/yashmgupta/super-telegram/issues)
- 💡 [Request a feature](https://github.com/yashmgupta/super-telegram/issues/new)
- ⭐ Star this repository if you find it useful!

---

<div align="center">

Made with ❤️ by [yashmgupta](https://github.com/yashmgupta)

**[⬆ Back to Top](#-super-telegram)**

</div>