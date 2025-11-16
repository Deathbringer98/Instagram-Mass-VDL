# IGDL – Instagram Bulk Downloader (Interactive)

`IGDL.py` is a simple and powerful Instagram downloader that lets you paste **any Instagram Post or Reel URL** and download them in bulk.  
It supports:

- Reels  
- Video posts  
- Image posts  
- Multi-image carousels  
- Mixed media posts  

The script cleans filenames, handles multi-item posts, and saves everything neatly in a folder.

---

## ✅ Features

- **Interactive mode** — script asks you to paste links  
- **Clean filenames** (no emojis or illegal characters)  
- **Downloads any public Instagram media**  
- **Handles multi-item posts (carousels)**  
- **Bulk downloads**  
- **Uses yt-dlp for reliability**  
- Saves videos/photos to:  
  ```
  ig_downloads/
  ```

---

## 📦 Requirements

Install the downloader dependency:

```sh
pip install yt-dlp
```

---

## ▶️ How to Run

Open PowerShell or Terminal in the script folder and run:

```sh
python IGDL.py
```

You will see:

```
Enter Instagram URLs (Reels or Posts), one per line.
Press ENTER on an empty line when done:

> https://www.instagram.com/reel/ABC123/
> https://www.instagram.com/p/XYZ456/
> 
```

All downloads will begin automatically.

---

## 📁 Where Files Are Saved

Files are stored in:

```
./ig_downloads/
```

Examples:

```
My_Reel_Clip_13482.mp4
Cool_Photo_Album_89234.mp4
```

Instagram posts with multiple items are saved individually.

---

## 🛠 How It Works

1. The script prompts for URLs  
2. User pastes one Instagram link per line  
3. `yt-dlp` fetches and downloads all media  
4. Script renames files safely:  
   - Removes emojis  
   - Removes symbols  
   - Removes illegal filesystem characters  
   - Replaces spaces with underscores  
5. Every downloaded file is stored in `ig_downloads/`  
6. Carousel posts download each item separately

---

## 💡 Notes

- Works with **public** Instagram content  
- If a download fails, updating yt-dlp usually fixes it:

```sh
pip install -U yt-dlp
```

- You can paste as many URLs as you want  

---

## 🔧 Optional Upgrades

Available on request:

- Load links from a `.txt` file  
- Auto-save links to `.txt`  
- Multi-thread download acceleration  
- Auto-login Instagram with cookies  
- Download entire Instagram profiles  
- Proxy rotation  
- Auto rename using date/user/type patterns  

---

## ✔ License

MIT License. Free to modify and distribute.

---
