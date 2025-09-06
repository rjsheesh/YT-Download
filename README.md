# YT-Download 🎥

**YouTube Downloader GUI** একটি সহজ এবং শক্তিশালী টুল যা Windows এ কাজ করে।  
এই টুল দিয়ে তুমি:

- Video / Audio (MP3) ডাউনলোড করতে পারবে
- Playlist সম্পূর্ণ ডাউনলোড সাপোর্ট
- Dark theme + Thumbnail preview
- Download progress bar + Status
- Default download folder: `YT Download` (auto-create)

---

## Features

- ✅ Video/Audio (MP3) download  
- ✅ Playlist support  
- ✅ Dark theme GUI  
- ✅ Thumbnail preview for each video  
- ✅ Progress bar showing download percentage  
- ✅ Multithreading (GUI freeze হয় না)  
- ✅ Default folder `YT Download` auto-create  

---

## Installation

**Step 1:** Clone the repo

```bash
git clone https://github.com/rjsheesh/YT-Download.git
cd YT-Download
```

**Step 2:** Install required packages

```bash
pip install -r requirements.txt
```

**Step 3:** Install FFmpeg

- Windows: Download from [FFmpeg](https://ffmpeg.org/download.html)  
- Extract and set path to `C:\ffmpeg\bin` (or update `FFMPEG_PATH` in code)  

---

## Usage

Run the GUI tool:

```bash
python main.py
```

- Enter YouTube URL  
- Select format (Video / Audio)  
- Select quality  
- Optional: Check "Download Entire Playlist"  
- Click **Download**  

> By default, all downloads go to `YT Download` folder.  
> You can select a different folder if you want.

---

## Requirements

- Python 3.8+  
- Packages:

```txt
yt-dlp
pillow
requests
```

---

## Notes

- Ensure FFmpeg path is correctly set.  
- Works best on Windows. Linux/Mac may need slight path adjustments.  
- Playlist downloads fetch all videos sequentially.  

---

## License

MIT License
