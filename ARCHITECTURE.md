# ARCHITECTURE

## Overview

WISTA is designed as a modular, decentralized composition of components.
Each responsibility is intentionally separated.

This is a technical and philosophical decision.

---

## Core Layers

### Search & Metadata

Search and metadata are handled via **Invidious-compatible sources**.

This allows:
- Searching without official APIs
- Reduced dependency on Google accounts
- Decoupling discovery from playback

Invidious demonstrates that metadata access does not need to be platform-owned.

---

### Content Resolution Layer

**yt-dlp** is used as an experimental resolver.

Its role:
- Resolve available video/audio streams
- Extract format and codec information
- Provide dynamic access to upstream platforms

yt-dlp is treated as an interchangeable access layer, not a dependency to hide.

---

### Frontend Player

The frontend is a web-based SPA responsible for:
- UI and interaction
- Playback logic
- Client-side experimentation

The frontend does not own search or resolution logic.

---

### Hosting & Deployment

WISTA favors static and edge-friendly deployment:
- GitHub Pages
- Edge platforms (Cloudflare, Deno)
- Self-hosted environments

Hosting is intentionally flexible.

---

## Design Intent

- Each layer can be replaced independently
- Self-hosting is always an option
- Forking is expected, not discouraged
- Failure of one component should not collapse the system

This architecture prioritizes **freedom over convenience**.
