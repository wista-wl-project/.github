# 🎬 wista-project
![Open Source](https://img.shields.io/badge/Open%20Source-Yes-brightgreen)
![YouTube Alternative](https://img.shields.io/badge/YouTube-Alternative-red)
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Vue](https://img.shields.io/badge/Vue.js-4FC08D?logo=vue.js&logoColor=white)

---

## 🌍 About wista-project

**wista-project** is an open-source organization exploring  
**YouTube alternatives and decentralized video consumption on the web**.

We believe that video platforms should not be locked behind
opaque algorithms, forced accounts, or centralized control.

Our goal is to experiment with **freer, more modular, and more transparent**
ways to search, access, and watch video content on the open web.

---

## 🎯 Philosophy

- Avoid dependency on a single centralized video platform
- Separate *search*, *metadata*, *delivery*, and *playback*
- Favor open-source tools and inspectable architectures
- Enable experimentation, forks, and self-hosting
- Keep the web accessible for individuals and small communities

This project is **not a clone of YouTube**,  
but an exploration of **alternative architectures**.

---

## 🧩 Architecture & Ideas

### 🔍 Invidious (Search & Metadata)

We use **Invidious** as a reference and integration point for:
- Searching YouTube content without official APIs
- Accessing metadata without user tracking
- Reducing reliance on Google accounts

Invidious demonstrates how search and metadata can be
**decoupled from the original platform**.

---

### 📥 yt-dlp (Content Access Layer)

**yt-dlp** is used as an experimental backend tool to:
- Resolve video streams and formats
- Extract media URLs dynamically
- Explore client-side or proxy-based playback approaches

This layer allows WISTA to remain **format-agnostic**  
and adaptable to changes in upstream platforms.

---

### 🌐 Decentralized & Modular Design

Instead of a monolithic platform, WISTA is designed as a **composition of parts**:

- Search providers (e.g. Invidious)
- Stream resolvers (e.g. yt-dlp)
- Frontend players (Web-based SPA)
- Hosting options (GitHub Pages, edge platforms, self-hosting)

Each component can be replaced, modified, or self-hosted.

This modularity is intentional.

---

## 🚀 Main Project

### 🎧 WISTA

A web-based YouTube alternative focused on:
- Clean UI
- Client-side experimentation
- Flexible backends
- Modern frontend architecture

- 🌐 Website: https://wista-project.github.io
- 📁 Repository: https://github.com/wista-project/wista-project.github.io

Built mainly as a **Single Page Application (SPA)**.

---

## 🛠 Tech Stack

### Languages & Runtimes
- Node.js
- Python
- TypeScript
- JavaScript
- HTML / CSS

### Frontend
- React
- Vue.js
- Vite
- Tailwind CSS

### Platforms
- GitHub Pages
- Cloudflare
- Render / Replit / Deno

---

## 🤝 Contributing

Contributions are welcome — especially from people interested in:
- Alternative video platforms
- Decentralized web architecture
- Privacy-friendly tooling
- Experimental frontend design

Please see individual repositories for details.

---

## 📫 Contact

📧 **Email:** wista-project@outlook.jp  
🐙 **GitHub:** https://github.com/wista-wl-project

---

## 🇯🇵 日本語（概要）

**wista-project** は、  
YouTube に依存しない動画視聴体験を探求する  
オープンソースプロジェクトです。

Invidious・yt-dlp などのツールを活用し、  
検索・取得・再生を分離した  
**分散的・実験的な構成**を重視しています。

巨大プラットフォームに縛られない  
「もう一つの選択肢」を作ることが目的です。

---

## 📄 License

Each repository defines its own license.  
See individual projects for details.
