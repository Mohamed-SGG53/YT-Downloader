# 🎬 YouTube Downloader GUI - Developed by Mohamed Hisham

### 🎯 Core Features
- **Video & Audio Download**: Download YouTube videos in various qualities (144p to 4K)
- **Audio Extraction**: Extract audio-only in MP3/M4A format with embedded thumbnails
- **Multiple Formats**: Support for MP4, WebM, MKV, and more
- **Bulk Download**: Support for playlists and multiple videos
- **Thumbnail Embedding**: Automatically embeds video thumbnails into downloaded video & audio files (MP4/MP3)

### 🎨 User Interface
- **Dark/Light Themes**: Switch between modern dark and light modes
- **Multi-Language**: Full Arabic and English support
- **Intuitive Design**: Clean and user-friendly interface
- **Thumbnail Preview**: See video thumbnails before downloading
- **Progress Tracking**: Real-time download progress with percentage

### 🔧 Advanced Features
- **Auto Update System**: One-click updates with GitHub integration
- **Download History**: Keep track of all downloads with file status
- **Smart Detection**: Automatic duplicate file detection
- **Quality Selection**: Choose from available resolutions and formats
- **Clipboard Integration**: Paste URLs directly from clipboard
- **System Tray**: Minimize to system tray for background operation

### 🚀 Performance
- **High Speed**: Multi-threaded downloading with aria2c integration
- **Resume Support**: Resume interrupted downloads
- **Batch Processing**: Efficient handling of multiple downloads
- **Low Resource Usage**: Optimized for smooth operation

## 📦 Installation

### Option 1: Download Executable (Recommended for Windows)
1. Download the latest `YT Downloader.zip` from [Releases](https://github.com/Mohamed-SGG53/YT-Downloader/releases)
2. Run the executable - no installation required!

### 📋 Requirements
- Windows 10/11 (64-bit)
- Internet connection

## 🛠️ Technical Details

### Built With
- **Python**: Core programming language
- **Tkinter**: GUI framework
- **yt-dlp**: YouTube downloading engine
- **FFmpeg**: Media processing and thumbnail embedding
- **aria2c**: High-speed downloading
- **Pillow**: Image processing for thumbnails

### Architecture
- **Modular Design**: Separate modules for UI, downloading, and utilities
- **Multi-threading**: Non-blocking UI during downloads
- **Error Handling**: Comprehensive error recovery system
- **Auto-update**: Self-updating capability via GitHub releases

## 📖 How to Use

### Basic Usage
1. **Paste URL**: Copy and paste any YouTube video URL
2. **Analyze Video**: Click "Analyze Video" to see available qualities
3. **Choose Quality**: Select your preferred resolution from the list
4. **Select Folder**: Choose download location
5. **Download**: Click "Download" and wait for completion

### Advanced Features
- **Audio Download**: Select "Audio Only" format for MP3 extraction with automatic thumbnail embedding
- **History Tab**: View, play, or delete previous downloads
- **Settings**: Customize theme, language, and preferences
- **System Tray**: Right-click tray icon for quick access

## 🎯 Supported Formats

### Video Formats
- MP4 (H.264, H.265/HEVC)
- Up to 4K resolution (when available)

### Audio Formats
- MP3 (128-320 kbps) with embedded thumbnail artwork

## 🔧 Configuration

### Settings Menu
- **Theme**: Light/Dark mode toggle
- **Language**: Arabic/English interface
- **Download Path**: Default download folder
- **Update Check**: Automatic update notifications

### Advanced Options
- Concurrent downloads limit
- Retry attempts on failure
- File naming conventions
- Proxy settings (if needed)

## 📁 Project Structure

```
YT-Downloader/
└── YouTube Downloader.exe
└── _internal/              # Embedded dependencies
    ├── nodejs/             # JavaScript runtime
    ├── ffmpeg/             # Media processing (includes thumbnail embedding)
    └── aria2c.exe          # Download accelerator
```

## 🆓 Free Software Notice

**Important**: This software is completely FREE and open-source. However, please note:
- The source code is not publicly shared by the developer
- All features are available at no cost
- No premium versions or paid upgrades
- No advertisements or bundled software
- No user data collection or tracking

## 🐛 Troubleshooting

### Common Issues & Solutions

**Problem**: "FFmpeg not found" error  
**Solution**: Ensure FFmpeg is in the `_internal/ffmpeg/` folder

**Problem**: Download stuck at 0%  
**Solution**: Check internet connection and try a different video

**Problem**: "JavaScript runtime required"  
**Solution**: Node.js is included in the package - reinstall if missing

**Problem**: Can't update the application  
**Solution**: Run as administrator or check firewall settings

**Problem**: Thumbnail not showing in audio files  
**Solution**: Ensure FFmpeg is properly installed and has write permissions

## 📄 License

This project is completely FREE to use. While the source code is not shared, users are free to:
- Use the software for personal and commercial purposes
- Distribute the software to others
- Report bugs and suggest features

## 🙏 Acknowledgments

- **yt-dlp** team for the amazing YouTube downloading library
- **FFmpeg** for powerful media processing and thumbnail embedding
- **aria2** for high-speed downloading
- All contributors and users of this project

## 📞 Support

- **GitHub Issues**: [Report Bugs & Features](https://github.com/Mohamed-SGG53/YT-Downloader/issues)

---

⭐ **If you find this project useful, please give it a star on GitHub!** ⭐

Built with ❤️ by [Mohamed Hisham](https://github.com/Mohamed-SGG53)

---

**Last Updated**: 3/12/2025
**Version**: 1.0.0  
**Status**: Actively Maintained 🟢
