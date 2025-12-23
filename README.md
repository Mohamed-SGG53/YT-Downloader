
---

# 🎬 YouTube Downloader GUI

**Developed by Mohamed Hisham**

---

## 🎯 Features

* Download YouTube videos in multiple qualities (144p up to 4K)
* Audio-only download (MP3 / M4A) with embedded thumbnail
* Supports MP4, WebM, MKV formats
* Playlist & bulk downloads
* Automatic thumbnail embedding for video and audio files

## 🎨 User Interface

* Dark & Light modes
* Arabic & English language support
* Clean and easy-to-use design
* Video thumbnail preview before download
* Real-time download progress

## 🎯 Supported Formats

### Video Formats

* MP4 (H.264, H.265 / HEVC)
* Up to 4K resolution (when available)

### Audio Formats

* MP3 (128–320 kbps) with embedded thumbnail artwork

## 🚀 Performance

* High Speed: Multi-threaded downloading with aria2c integration
* Resume Support: Resume interrupted downloads
* Batch Processing: Efficient handling of multiple downloads
* Low Resource Usage: Optimized for smooth operation

## 📦 Installation

### Option 1: Download Executable (Recommended for Windows)

1. Download `YT Downloader.zip` from the Releases page
2. Run the executable — no installation required

### 📋 Requirements

* Windows 10 / 11 (64-bit)
* Internet connection

## 🛠️ Built With

* Python
* Tkinter
* yt-dlp
* FFmpeg
* aria2c
* Pillow

## 📁 Project Structure

```
YT-Downloader/
└── YouTube Downloader.exe
└── _internal/
    ├── nodejs/     # JavaScript runtime
    ├── ffmpeg/     # Media processing & thumbnail embedding
    └── aria2c.exe  # Download accelerator
```

## 🐛 Troubleshooting

* FFmpeg not found: Ensure FFmpeg exists in `_internal/ffmpeg/`
* Download stuck at 0%: Check your internet connection or try another video
* JavaScript runtime required: Node.js is included — reinstall if missing
* Can't update the application: Run as administrator or check firewall settings
* Thumbnail not embedded in audio: Make sure FFmpeg has write permissions

## 📄 License

This software is completely FREE to use. Users are allowed to:

* Use it for personal or commercial purposes
* Distribute it freely
* Report bugs and suggest new features

## 🙏 Acknowledgments

* yt-dlp team
* FFmpeg
* aria2
* All contributors and users

## 📞 Support

* GitHub Issues: Report bugs & feature requests

⭐ If you find this project useful, please give it a star on GitHub ⭐

Built with ❤️ by **Mohamed Hisham**

---

# 🎬 YouTube Downloader GUI

**تم التطوير بواسطة محمد هشام**

## 🎯 المميزات

* تحميل فيديوهات يوتيوب بجودات متعددة (من 144p حتى 4K)
* تحميل الصوت فقط (MP3 / M4A) مع دمج الصورة المصغّرة
* دعم صيغ MP4 و WebM و MKV
* تحميل قوائم التشغيل والتحميل الجماعي
* دمج الصورة المصغّرة تلقائيًا داخل الملفات

## 🎨 واجهة المستخدم

* وضع داكن وفاتح
* دعم اللغتين العربية والإنجليزية
* واجهة بسيطة وسهلة الاستخدام
* معاينة صورة الفيديو قبل التحميل
* عرض تقدّم التحميل بشكل لحظي

## 🎯 الصيغ المدعومة

### صيغ الفيديو

* MP4 (H.264, H.265 / HEVC)
* دعم دقة تصل إلى 4K (حسب توفر الفيديو)

### صيغ الصوت

* MP3 (من 128 إلى 320 كيلوبِت/ثانية) مع صورة مدمجة

## 🚀 الأداء

* سرعة عالية باستخدام التحميل متعدد الخيوط مع aria2c
* استكمال التحميلات المتوقفة
* تحميل دفعات بكفاءة عالية
* استهلاك منخفض لموارد الجهاز

## 📦 التشغيل

### الخيار الموصى به (ويندوز)

1. تحميل ملف `YT Downloader.zip`
2. تشغيل البرنامج مباشرة بدون تثبيت

### 📋 المتطلبات

* Windows 10 / 11 (64-bit)
* اتصال بالإنترنت

## 🛠️ التقنيات المستخدمة

* Python
* Tkinter
* yt-dlp
* FFmpeg
* aria2c
* Pillow

## 📁 هيكلة المشروع

```
YT-Downloader/
└── YouTube Downloader.exe
└── _internal/
    ├── nodejs     # محرك JavaScript
    ├── ffmpeg     # معالجة الوسائط ودمج الصور
    └── aria2c.exe # مسرّع التحميل
```

## 🐛 استكشاف الأخطاء

* FFmpeg غير موجود: تأكد من وجوده داخل `_internal/ffmpeg/`
* التحميل متوقف عند 0%: تحقق من اتصال الإنترنت أو جرّب فيديو آخر
* طلب JavaScript runtime: Node.js مدمج داخل البرنامج
* فشل التحديث: شغّل البرنامج كمسؤول أو افحص جدار الحماية
* عدم ظهور الصورة داخل ملف الصوت: تأكد من صلاحيات FFmpeg

## 📄 الرخصة

البرنامج مجاني بالكامل، ويسمح بـ:

* الاستخدام الشخصي والتجاري
* إعادة التوزيع
* الإبلاغ عن الأخطاء واقتراح المميزات

## 🙏 شكر وتقدير

* فريق yt-dlp
* FFmpeg
* aria2
* جميع المستخدمين والداعمين

## 📞 الدعم

* GitHub Issues للإبلاغ عن المشاكل وطلب المميزات

⭐ إذا أعجبك المشروع لا تنسَ دعمه بنجمة على GitHub ⭐

تم التطوير بكل ❤️ بواسطة **محمد هشام**

---
