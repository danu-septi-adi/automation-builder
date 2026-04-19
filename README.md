# 🚀 DANU Web Automation Builder

> Generate web automation script tanpa coding ribet.

🌐 **Live Demo:**  
👉 https://danu-septi-adi.github.io/automation-builder/

---

## ✨ Overview

DANU Web Automation Builder adalah tools berbasis web untuk membuat script otomatisasi browser secara visual.

Tanpa perlu coding manual, kamu bisa:
- Menyusun flow automation
- Generate script Puppeteer otomatis
- Jalankan bot langsung di Node.js

---

## 🔥 Features

- 🧩 Drag & Drop Automation Builder
- ⚡ Generate Puppeteer Script otomatis
- 🕵️ Stealth Mode (anti detection)
- 🔁 Self-Healing (auto retry jika gagal)
- 🚀 Turbo Mode (lebih cepat & hemat resource)
- 🎯 Multiple Selector:
  - CSS
  - XPath
  - Text-based
  - Coordinate (X,Y)
- 💾 Auto Save (localStorage)

---

## 🖥️ Demo

Coba langsung di browser:  
👉 https://danu-septi-adi.github.io/automation-builder/

---

## ⚙️ Installation (Untuk Run Script)

Install dependency:

```bash
npm init -y
npm install puppeteer puppeteer-extra puppeteer-extra-plugin-stealth
```

---

## 🚀 Cara Pakai

### 1. Buka Web
Akses:
```
https://danu-septi-adi.github.io/automation-builder/
```

---

### 2. Buat Automation Flow
- Klik **+ Action**
- Pilih action:
  - Navigate
  - Click
  - Type
  - Wait / Delay

---

### 3. Generate Script
Klik:
```
COMPILE STEALTH ENGINE
```

---

### 4. Jalankan Script

Copy hasil → simpan sebagai:
```
bot.js
```

Run:
```bash
node bot.js
```

---

## 🧠 Use Case

- Auto login website
- Bot klik otomatis
- Auto input form
- Web scraping sederhana
- Automation testing

---

## 🛠️ Advanced Features

### 🔁 Self-Healing
Script akan retry jika element tidak ditemukan.

### 🚀 Turbo Mode
Blok:
- Image
- Font
- Media

➡️ Hasil:
- Lebih cepat
- Lebih hemat RAM

---

## ⚠️ Error Handling

Jika gagal:
- Otomatis generate:
```
final_error.png
```

Gunakan untuk debug.

---

## 📁 Structure

```
automation-builder/
├── index.html
├── README.md
```

---

## 🧪 Tech Stack

- HTML
- Tailwind CSS
- Vanilla JavaScript
- Puppeteer
- puppeteer-extra
- Stealth Plugin

---

## 📌 Notes

Pastikan path Chrome sesuai:

```js
executablePath: 'C:\\Program Files\\Google\\Chrome\\Application\\chrome.exe'
```

---

## 💡 Roadmap

- Import / Export JSON flow
- Multi-tab automation
- Cloud execution
- Scheduler bot

---

## 👨‍💻 Author

**Danu Septi Adi**

---

## ⭐ Support

Kalau project ini membantu:
- ⭐ Star repo
- 🔄 Share ke teman
- 🛠️ Contribute