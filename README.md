# HEIC to JPG Converter (Client-Side)

A fast, privacy-friendly **HEIC / HEIF → JPG** converter that runs entirely in the browser.  
No uploads, no servers — all conversion happens locally on the user’s device.

Supports:
- Drag & drop or file picker
- Batch conversion
- Adjustable JPG quality
- Individual downloads or ZIP download of all files

---

## Demo

You can deploy this instantly using **GitHub Pages** or open the HTML file locally.

---

## Features

- Drag-and-drop HEIC / HEIF support
- Adjustable JPEG quality slider
- Live image previews after conversion
- Batch ZIP download
- Fully client-side (no file uploads)
- Fast conversion using WebAssembly-backed libraries

---

## How It Works

This tool uses two open-source libraries loaded via CDN:

- **heic2any** — Converts HEIC/HEIF images to JPEG in the browser
- **JSZip** — Packages converted images into a downloadable ZIP

All processing happens locally. Your images never leave your machine.

---

## Usage

### Option 1: Open Locally

1. Download or clone the repository
2. Open `index.html` in a modern browser (Chrome, Edge, Firefox)

### Option 2: GitHub Pages (Recommended)

1. Push the project to a GitHub repository
2. Go to **Settings → Pages**
3. Set source to `main` branch (root)
4. Visit the provided URL

---

## Supported Browsers

- Chrome (recommended)
- Edge
- Firefox
- Safari (macOS)

> Note: iOS Safari HEIC support may vary depending on device and OS version.
