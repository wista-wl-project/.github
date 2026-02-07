# Architecture Diagram (Textual)

User
 ↓
Frontend SPA (WISTA UI)
 ↓
Search Layer (Invidious-compatible)
 ↓
Metadata Resolution
 ↓
Content Resolver (yt-dlp)
 ↓
Upstream Video Platform

---

## Key Properties

- No single point of ownership
- Each arrow represents a replaceable boundary
- Any layer can be removed or swapped

This is intentional.
