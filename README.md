# 🎵 Music Player

A clean, responsive web music‑player that lets you upload songs, build playlists, and enjoy them in either light or dark mode—all without any backend setup. Everything runs right in your browser. :contentReference[oaicite:7]{index=7}

## ✨ Features
- **Local file playback** – drag‑and‑drop or use *Upload Music* to add MP3/WAV files. :contentReference[oaicite:8]{index=8}  
- **Playlist management** – create, save, load, and delete playlists (stored in `localStorage`). :contentReference[oaicite:9]{index=9}  
- **Search & filter** within the current playlist. :contentReference[oaicite:10]{index=10}  
- **Dark / Light theme toggle** with a single click. :contentReference[oaicite:11]{index=11}  
- **Keyboard shortcuts**: `Space` (play/pause), `→` (next), `←` (previous). :contentReference[oaicite:12]{index=12}  
- **Fully responsive UI** built with Tailwind CSS and a pinch of custom CSS.   

## 🛠 Tech Stack
| Layer | Tools |
|-------|-------|
| Mark‑up | HTML5 |
| Styling | Tailwind CSS CDN, custom CSS |
| Logic   | Vanilla JavaScript |

## 🚀 Getting Started
```bash
# 1. Clone the repo
git clone https://github.com/your‑username/your‑repo.git
cd your‑repo

# 2. Launch (any of the following)
#   – double‑click index.html
#   – or use a simple http server for live reload
npx serve .
Tip: GitHub Pages works out of the box—just push to main and enable Pages in repo settings.

🗂 Project Structure
bash
Copy
Edit
📂 your‑repo
├─ index.html   # UI markup + JS logic
├─ style.css    # theme tweaks & responsive rules
└─ README.md    # this file
