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

**Last Updated**: 4/12/2025

**Version**: 1.0.0

**Status**: Actively Maintained 🟢

---

# 🎬 واجهة تحميل اليوتيوب - تم التطوير بواسطة محمد هشام

### 🎯 المميزات الأساسية

* **تحميل الفيديو والصوت**: تحميل فيديوهات يوتيوب بجودات مختلفة (من 144p حتى 4K)
* **استخراج الصوت فقط**: استخراج الصوت بصيغ MP3/M4A مع دمج الصورة المصغّرة تلقائيًا
* **صيغ متعددة**: دعم MP4 و WebM و MKV وغيرها
* **تحميل دفعات**: دعم تشغيل قوائم التشغيل والتحميل الجماعي
* **دمج الصورة المصغرة**: دمج صورة الفيديو داخل ملف الفيديو/الصوت تلقائيًا (MP4/MP3)

### 🎨 واجهة المستخدم

* **الوضع الليلي والفاتح**: التبديل بين ثيمات عصرية داكنة وفاتحة
* **متعدد اللغات**: دعم كامل للغتين العربية والإنجليزية
* **واجهة سهلة الاستخدام**: تصميم نظيف وبسيط
* **عرض الصورة المصغّرة**: مشاهدة صورة الفيديو قبل التحميل
* **تتبع التقدم**: عرض تقدّم التحميل بشكل لحظي مع النسبة المئوية

### 🔧 مميزات متقدمة

* **نظام التحديث التلقائي**: تحديث بنقرة واحدة مع تكامل GitHub
* **سجل التحميلات**: تتبع جميع الملفات المحمَّلة وحالتها
* **كشف ذكي**: اكتشاف الملفات المكررة تلقائيًا
* **اختيار الجودة**: اختيار الدقة والصيغة المتاحة
* **التكامل مع الحافظة**: لصق الروابط مباشرة من الحافظة
* **العمل بالخلفية**: إمكانية التصغير إلى شريط المهام (System Tray)

### 🚀 الأداء

* **سرعة عالية**: تحميل متعدد الخيوط مع دمج أداة **aria2c** لتسريع التحميل
* **استكمال التحميلات**: استمرار التحميل عند الانقطاع
* **تشغيل دفعات**: معالجة فعالة لعدة تحميلات
* **استهلاك منخفض**: أداء محسن لا يستهلك موارد كثيرة

## 📦 التثبيت

### الخيار 1: التحميل المباشر (موصى به لويندوز)

1. حمّل أحدث نسخة `YT Downloader.zip` من صفحة **Releases**
2. شغّل البرنامج مباشرة — بدون تثبيت!

### 📋 المتطلبات

* Windows 10/11 (64-bit)
* اتصال بالإنترنت

## 🛠️ التفاصيل التقنية

### تم بناءه باستخدام:

* **Python**: اللغة الأساسية
* **Tkinter**: واجهة المستخدم
* **yt-dlp**: محرك تحميل اليوتيوب
* **FFmpeg**: معالجة الوسائط ودمج الصور
* **aria2c**: تسريع التحميل
* **Pillow**: معالجة الصور

### الهندسة الداخلية

* **تصميم معياري**: فصل واجهة المستخدم والمنطق والمهام
* **تعدد الخيوط**: منع تجميد الواجهة أثناء التحميل
* **نظام أخطاء متكامل**: استرجاع عند حدوث أي مشكلة
* **تحديث تلقائي**: تحديث ذاتي عبر GitHub Releases

## 📖 كيفية الاستخدام

### الاستخدام الأساسي

1. **ضع الرابط**: انسخ والصق رابط فيديو اليوتيوب
2. **تحليل الفيديو**: اضغط "Analyze Video" لعرض الجودات المتاحة
3. **اختر الجودة**: اختر الدقة المناسبة
4. **اختر المجلد**: حدد مكان الحفظ
5. **تحميل**: اضغط "Download" وانتظر اكتمال التحميل

### المميزات المتقدمة

* **تحميل صوت فقط**: استخدم خيار "Audio Only" لاستخراج MP3 مع دمج صورة الفيديو تلقائيًا
* **علامة History**: عرض وتشغيل وحذف التحميلات السابقة
* **الإعدادات**: تخصيص الثيم واللغة والمسار الافتراضي
* **شريط النظام**: خيارات سريعة من أيقونة البرنامج

## 🎯 الصيغ المدعومة

### صيغ الفيديو

* MP4 (H.264, H.265/HEVC)
* يدعم حتى 4K حسب توفر الفيديو

### صيغ الصوت

* MP3 (من 128 إلى 320 kbps) مع صورة مدمجة

## 🔧 الإعدادات

### من قائمة الإعدادات

* **الثيم**: تبديل اللون الداكن والفاتح
* **اللغة**: عربي/إنجليزي
* **مسار التحميل**: اختيار المجلد الافتراضي
* **التحديث**: إشعار بالتحديثات الجديدة

### خيارات متقدمة

* عدد التحميلات المتزامنة
* عدد محاولات الإعادة عند الفشل
* طريقة تسمية الملفات
* إعدادات البروكسي (عند الحاجة)

## 📁 هيكلة المشروع

```
YT-Downloader/
└── YouTube Downloader.exe
└── _internal/              # الملفات المدمجة داخل البرنامج
    ├── nodejs/             # محرك JavaScript
    ├── ffmpeg/             # معالجة الفيديو (مع دعم دمج الصور)
    └── aria2c.exe          # مسرّع التحميل
```

## 🆓 ملاحظة حول مجانية البرنامج

**مهم**: البرنامج مجاني 100% ومفتوح الاستخدام. لكن:

* الكود المصدري غير متاح للجمهور
* لا يوجد أي إصدار مدفوع
* لا يحتوي على إعلانات أو برامج مرفقة
* لا يتم جمع أي بيانات من المستخدم

## 🐛 استكشاف الأخطاء

### مشاكل شائعة وحلولها

**المشكلة**: رسالة "FFmpeg not found"
**الحل**: تأكد من وجود FFmpeg داخل مجلد `_internal/ffmpeg/`

**المشكلة**: التحميل عالق عند 0%
**الحل**: تحقق من اتصال الإنترنت أو جرّب فيديو آخر

**المشكلة**: "JavaScript runtime required"
**الحل**: Node.js مدمج داخل الحزمة — أعد التثبيت إن لزم

**المشكلة**: فشل التحديث
**الحل**: شغّل البرنامج كمسؤول أو تحقق من جدار الحماية

**المشكلة**: عدم ظهور الصورة داخل ملفات الصوت
**الحل**: تأكد أن FFmpeg مثبت بشكل صحيح ولديه صلاحيات الكتابة

## 📄 الرخصة

هذا المشروع مجاني بالكامل للاستخدام. ويمكن للمستخدمين:

* استخدام البرنامج شخصيًا أو تجاريًا
* إعادة توزيعه للآخرين
* تقديم اقتراحات وتبليغ عن الأخطاء

## 🙏 شكر وتقدير

* فريق **yt-dlp** لライبرري التحميل القوية
* **FFmpeg** لمعالجة الوسائط ودمج الصور
* **aria2** لتسريع التحميل
* كل المساهمين والمستخدمين

## 📞 الدعم

* **GitHub Issues**: للإبلاغ عن الأخطاء أو طلب المميزات

---

⭐ **إذا أعجبك المشروع لا تنسَ دعمه بنجمة على GitHub!** ⭐

تم التطوير بكل ❤️ بواسطة محمد هشام
**آخر تحديث**: 4/12/2025

**الإصدار**: 1.0.0

**الحالة**: يتم صيانته باستمرار 🟢


---
