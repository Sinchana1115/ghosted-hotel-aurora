# 👻 GHOSTED: Last Seen at Hotel Aurora

> *2:47 AM. Your best friend Aarav checks into Room 404. Then he goes silent.*

A slow-burn 3D mystery you play in the browser. Talk to the people who were there, climb to the second floor, piece together a 3-digit code, and open Aarav's luggage. No jump scares, no chasing, just a hotel that knows more than it says.

[![Play Now](https://img.shields.io/badge/▶_PLAY_NOW-ff6fcf?style=for-the-badge)](https://Sinchana1115.github.io/ghosted-hotel-aurora/)

**Live link:** https://Sinchana1115.github.io/ghosted-hotel-aurora/

---

## 🎮 How to play

1. Open the live link in **desktop Chrome** (headphones recommended).
2. Pick a mode and click to start.
3. Talk to **Priya** at reception, then **Meera** in Room 405. Both hold clues.
4. Open Room 404, search the bed, and crack the luggage lock.

| Key | Action |
|---|---|
| `W A S D` | Move |
| Mouse | Look around |
| `E` | Interact / talk |
| `1` `2` `3` | Choose a dialogue reply |
| `Shift` | Run |
| `Esc` | Pause |

### Modes
- **Story:** glowing markers and clear objectives
- **Detective:** objectives only
- **Noir:** no hints, pure deduction

---

## ✨ Features

- First-person 3D hotel with a lobby, a climbable staircase and a second-floor corridor
- Branching NPC dialogue with a typewriter effect and a cinematic letterbox
- Clue board that tracks the luggage code across characters and rooms
- Atmospheric VFX: flickering lights, lightning through the window, drifting dust, moonlight beams, neon signage, vignette
- Procedural ambient audio built with the Web Audio API
- Single-file build with no install and no backend

## 🛠️ Tech stack

- **three.js** (WebGL rendering)
- **Vanilla JavaScript, HTML and CSS**
- **Web Audio API**
- Hosted on **GitHub Pages**

## 🗺️ Roadmap

- [ ] AI-powered suspects (LangChain agents with memory and secrets)
- [ ] Flask backend with MySQL for saves and leaderboards
- [ ] Spacy-based clue extraction from in-game chats
- [ ] Hugging Face generated art and emotion-aware NPC replies
- [ ] More floors, more characters, multiple endings
- [ ] Cloud deployment (GCP / AWS / Azure)

## 🚀 Run locally

```bash
git clone https://github.com/YOUR-USERNAME/ghosted-hotel-aurora.git
cd ghosted-hotel-aurora
# open index.html in Chrome, or serve it:
python -m http.server 8006
```
Then visit `http://localhost:8006`.

## 🔐 Security note

This build contains no API keys or secrets. When the backend features land, keys will live in a local `.env` file (git-ignored) and be used server-side only.

## 📄 License

MIT. Add a `LICENSE` file if you want others to reuse it.

---

Made with 💜 by **Sinchana1115**. Feedback and PRs welcome.
