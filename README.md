# AI Tools Hub 🤖
### 164 Free AI Tools Directory - Your Gateway to AI Innovation

[![Live Demo](https://img.shields.io/badge/Live-Demo-667eea?style=for-the-badge)](https://try-free-ai-tools-hub.netlify.app)
[![Tools](https://img.shields.io/badge/Tools-164-764ba2?style=for-the-badge)](https://try-free-ai-tools-hub.netlify.app)
[![Categories](https://img.shields.io/badge/Categories-19-667eea?style=for-the-badge)](https://try-free-ai-tools-hub.netlify.app)

---

## 📖 Overview

AI Tools Hub is the most comprehensive, curated directory of **164 free and freemium AI tools** across **19 distinct categories**. Built to democratize access to AI technologies, this platform serves developers, students, researchers, businesses, and anyone seeking powerful AI solutions without financial barriers.

**Live URL:** [try-free-ai-tools-hub.netlify.app](https://try-free-ai-tools-hub.netlify.app)

---

## ✨ Features

### 🎨 Modern UI/UX
- **Theme-aware Lucide Icons** — Crisp SVG icons with purple gradient styling
- **Dark/Light Mode** — Persistent theme preference with smooth transitions
- **Responsive Design** — Optimized for mobile, tablet, and desktop (1–4 column grid)
- **Single-File PWA** — Manifest and service worker fully inlined, no separate files needed

### 🔍 Smart Discovery
- **Real-time Search** — Filter across tool names, descriptions, and categories instantly
- **Category Organization** — 19 categories with live tool counts
- **Free Forever Filter** — Quickly surface tools with no paid tiers at all
- **Recently Added Section** — Auto-displays new tools for first-time visitors (3-minute timer)

### ⚡ Performance
- **Single-File Architecture** — Zero build process, instant deployment via drag-and-drop
- **Inline PWA** — Manifest injected as blob URL, icon as data URI, no external files
- **Lightweight** — ~30KB Lucide CDN, optimized CSS/JS
- **Fast Loading** — Minimal dependencies, CDN-delivered assets

---

## 🗂️ Categories (19)

| Category | Tools | Highlights |
|---|---|---|
| Conversational AI | 21 | ChatGPT, Claude, Gemini, DeepSeek, Arena, Groq |
| Research & Analysis | 30 | Perplexity, NotebookLM, Elicit, Build Check, Trismik |
| Image & Video | 18 | Stable Diffusion, Leonardo.AI, CapCut, X-Pilot |
| Voice & Audio | 13 | ElevenLabs, Whisper, Otter.ai, Speechify |
| Coding & Development | 16 | GitHub Copilot, Codeium, Cursor 3, GitBar, CodeCanary |
| Writing & Content | 10 | Grammarly, QuillBot, Copy.ai, Rytr |
| Productivity & Business | 13 | Notion AI, Fireflies, Replyless, Ray, ProdShort |
| Design & Creativity | 8 | Canva, Wonder, Design Arena, Fontjoy, Khroma |
| AI Automation | 11 | Sim AI, Project Supermind, Logic, Orange Slice, Lindy AI |
| Open-Source Models | 6 | Hugging Face, LM Studio, Pinokio, Ollama |
| No-Code Builders | 5 | Draftly, Brila, Bubble Mobile, Shipable AI |
| Utilities | 4 | GhostDesk, Claudoscope, TinyWow, Adobe Enhanced Speech |
| SEO & Marketing | 4 | ClayHog, AnswerThePublic, Simplified, Writesonic |
| Music Generation | 2 | Suno AI, Udio |
| Translation & Language | 4 | DeepL, Google Translate, LibreTranslate, Reverso |
| AI Security & Privacy | 2 | Emotion Sense Pro, Oblitaratus |
| AI Project Management | 1 | Portals |
| AI Resume & Career | 1 | Huntr AI Resume |
| AI Browsers | 1 | Dia Browser |

---

## 🚀 Recently Added (May 2026)

**Conversational AI:** Arena (LM Arena)

**Coding & Development:** GitBar, CodeCanary, Gemini CLI Subagents, Skills Janitor, Cursor 3

**AI Automation:** Sim AI, Project Supermind, Logic, Orange Slice, Microsoft Agent Framework

**Design & Creativity:** Wonder, Design Arena

**Open-Source Models:** Pinokio

**No-Code Builders:** Draftly, Brila

**Research & Analysis:** Trismik, Build Check

**Productivity & Business:** Replyless, Ray, ProdShort

**Image & Video:** X-Pilot

**SEO & Marketing:** ClayHog

**Utilities:** GhostDesk, Claudoscope

---

## 🛠️ Tech Stack

| Layer | Technology | Purpose |
|---|---|---|
| Frontend | HTML5 + CSS3 + Vanilla JS | Single-file architecture, zero dependencies |
| Icons | Lucide Icons (jsDelivr CDN) | Theme-aware SVG icons (~30KB) |
| Storage | LocalStorage | Theme preference, visit tracking |
| PWA | Inline Blob Manifest + Data URI Icon | Installable app, no separate files |
| Hosting | Netlify | Global CDN, drag-and-drop deploy |
| Analytics | Google Analytics (optional) | Usage tracking |

---

## 📦 Installation

### Option 1: Use Live Version
Visit [try-free-ai-tools-hub.netlify.app](https://try-free-ai-tools-hub.netlify.app)

### Option 2: Deploy Your Own

**Deploy to Netlify (Recommended)**
1. Download `index.html` from this repository
2. Drag it to [app.netlify.com/drop](https://app.netlify.com/drop)
3. Done — your site is live instantly on Netlify's global CDN

> No manifest.json, service-worker.js, or icon.svg needed. Everything is inlined into the single HTML file.

**Local Development**
```bash
# No build process needed — just open the file
open index.html

# Or serve with any static server
python -m http.server 8000
# Visit http://localhost:8000
```

---

## 🎨 Customization

### Change Theme Colors
Edit CSS variables in `<style>`:
```css
:root {
  --gradient-start: #667eea;  /* Purple */
  --gradient-end: #764ba2;    /* Darker purple */
}
```

### Add New Tools
Edit the `tools` array in JavaScript:
```javascript
const tools = [
  {
    name: "Your Tool",
    url: "https://yourtool.com",
    description: "What it does",
    category: "Conversational AI",
    tags: ["Free Tier"],  // or "Free Forever"
    new: true             // Shows "New" badge
  },
  // ... existing tools
];
```

### Modify Icon Mapping
Edit `iconMap` to change category icons:
```javascript
const iconMap = {
  "Conversational AI": "message-circle",
  "Your Category": "icon-name"  // Any Lucide icon
};
```
Browse Lucide icons: [lucide.dev/icons](https://lucide.dev/icons)

---

## 📊 Tool Selection Criteria

Tools are included based on strict criteria:

- ✅ Free tier with meaningful functionality
- ✅ OR completely free forever with no paid tiers
- ✅ No credit card required for free tier signup
- ✅ Active development and regular updates
- ✅ Positive user reviews and adoption
- ✅ Clear value proposition and use cases

---

## 🤝 Contributing

Want to suggest a tool? Open an issue with:
- Tool name and URL
- Description (1–2 sentences)
- Category fit
- Proof of free tier (screenshot or link to pricing page)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 👨‍💻 Built By

**Farman J — AI Generalist**

- Portfolio: [farman024.github.io/Farman-J](https://farman024.github.io/Farman-J)
- Twitter: [@Farman__24__](https://twitter.com/Farman__24__)
- Website: [try-free-ai-tools-hub.netlify.app](https://try-free-ai-tools-hub.netlify.app)

---

## 🌟 Acknowledgments

Built with:
- [Lucide Icons](https://lucide.dev) — Beautiful open-source SVG icons
- [Netlify](https://netlify.com) — Hosting and global CDN
- Inspiration from the AI community

---

## 📈 Roadmap

### Phase 1: Q2 2026
- [x] 164 tools across 19 categories
- [ ] User ratings system
- [ ] Tool comparison feature
- [ ] Mobile app (iOS/Android)

### Phase 2: Q3 2026
- [ ] AI-powered recommendation engine
- [ ] User accounts for favorites
- [ ] API access for developers
- [ ] Integration tutorials

### Phase 3: Q4 2026
- [ ] 200+ tools across 25+ categories
- [ ] Multi-language support
- [ ] Enterprise version
- [ ] AI tool marketplace

---

⭐ Star this repo if you find it useful!

[Visit AI Tools Hub →](https://try-free-ai-tools-hub.netlify.app)
