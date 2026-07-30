# 🤖 Gemini Voice AI Backend

Gemini Voice AI Backend is the core intelligence system for the web-based voice assistant project. It processes server-side communications, validates requests, securely interfaces with the Google Gemini API, and prepares responses for the browser interface.

The system handles Arabic voice data processing, ensures secure API key management via server proxies, and maintains stable execution on PHP-based hosting environments.

---

## ✨ Features

- 🔒 Secure Server-Side API Proxy (`process.php` & `config.php`)
- 🤖 AI Response Generation using Google Gemini (`gemini-3.6-flash`)
- 🌐 Browser-Based Web Speech Integration
- 🛡️ Built-in Error Handling & Detailed Exception Reporting
- ⚡ Lightweight, Framework-Free Architecture

---

## 🛠️ Technologies Used

- PHP 8.1+ (cURL)
- Google Gemini API
- Vanilla JavaScript (Web Speech API)
- HTML5 & CSS3
- InfinityFree Web Hosting

---

## ⚙️ Core Files Structure

- **`index.html`** — Main user interface layout and controls.
- **`app.js`** — Client-side logic managing speech recognition and audio synthesis.
- **`style.css`** — Modern dark-themed styling and animations.
- **`process.php`** — Secure backend handler communicating with Gemini.
- **`config.php`** — Isolated configuration file storing the private API key.

---

## 📌 Notes

- Keeps the Gemini API key hidden securely on the server, preventing browser exposure.
- Fully compatible with free PHP hosting providers without requiring Node.js.
- Designed to work seamlessly with Google Chrome and Microsoft Edge.
