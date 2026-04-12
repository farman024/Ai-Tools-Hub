# AI Tools Hub 🤖

**139 Free AI Tools Directory - Your Gateway to AI Innovation**

[![Live Demo](https://img.shields.io/badge/demo-live-success)](https://try-free-ai-tools-hub.netlify.app)
[![Tools](https://img.shields.io/badge/tools-139-blue)](https://try-free-ai-tools-hub.netlify.app)
[![Categories](https://img.shields.io/badge/categories-19-purple)](https://try-free-ai-tools-hub.netlify.app)
[![PWA](https://img.shields.io/badge/PWA-enabled-orange)](https://try-free-ai-tools-hub.netlify.app)

---

## 📖 Overview

AI Tools Hub is the most comprehensive, curated directory of **139 free and freemium AI tools** across **19 distinct categories**. Built to democratize access to AI technologies, this platform serves developers, students, researchers, businesses, and anyone seeking powerful AI solutions without financial barriers.

**Live URL:** [try-free-ai-tools-hub.netlify.app](https://try-free-ai-tools-hub.netlify.app)

---

## ✨ Features

### 🎨 Modern UI/UX
- **Theme-aware Lucide Icons** - Crisp SVG icons with purple gradient styling
- **Dark/Light Mode** - Persistent theme preference with smooth transitions
- **Responsive Design** - Optimized for mobile, tablet, and desktop (1-4 column grid)
- **Progressive Web App** - Install on any device, works offline

### 🔍 Smart Discovery
- **Real-time Search** - Filter across tool names, descriptions, and categories
- **Category Organization** - 19 categories with tool counts
- **Free Forever Filter** - Quickly find completely free tools
- **Recently Added Section** - Auto-displays new tools for first-time visitors (3-minute timer)

### ⚡ Performance
- **Single-File Architecture** - Zero build process, instant deployment
- **Lightweight** - ~30KB Lucide CDN, optimized CSS/JS
- **Fast Loading** - Minimal dependencies, CDN-delivered assets
- **Offline Support** - Service worker caches for offline access

---

## 🗂️ Categories (19)

1. **Conversational AI** (20 tools) - ChatGPT, Claude, Gemini, DeepSeek, Groq, Meta AI, and more
2. **Research & Analysis** (27 tools) - Perplexity, NotebookLM, Elicit, Consensus, Scira AI, and more
3. **Image & Video** (17 tools) - Stable Diffusion, Leonardo.AI, CapCut, Runway, and more
4. **Voice & Audio** (13 tools) - ElevenLabs, Whisper, Otter.ai, Speechify, and more
5. **Coding & Development** (11 tools) - GitHub Copilot, Codeium, v0, Replit, and more
6. **Writing & Content** (10 tools) - Grammarly, QuillBot, Copy.ai, Rytr, and more
7. **Productivity & Business** (10 tools) - Notion AI, Fireflies, Dokie AI, Fern, and more
8. **Design & Creativity** (5 tools) - Canva, Chronicle, Fontjoy, Khroma, and more
9. **AI Automation** (4 tools) - Computer X, Flowstep, Lindy AI, Tanka
10. **Music Generation** (2 tools) - Suno AI, Udio
11. **Translation & Language** (4 tools) - DeepL, Google Translate, LibreTranslate, Reverso
12. **SEO & Marketing** (3 tools) - AnswerThePublic, Simplified, Writesonic
13. **Open-Source Models** (4 tools) - Hugging Face, LM Studio, Stable Diffusion WebUI
14. **Utilities** (2 tools) - Adobe Enhanced Speech, TinyWow
15. **No-Code Builders** (2 tools) - Bubble Mobile, Shipable AI
16. **AI Security & Privacy** (2 tools) - Emotion Sense Pro, Oblitaratus
17. **AI Project Management** (1 tool) - Portals
18. **AI Resume & Career** (1 tool) - Huntr AI Resume
19. **AI Browsers** (1 tool) - Dia Browser

---

## 🚀 Recently Added (29 Tools - April 2026)

**Conversational AI:** Minimax Claw, Qwen AI, ThunAI, Pi AI  
**AI Browsers:** Dia Browser  
**Image & Video:** Gogiberry, Vozo Visual Translate  
**Coding:** Kodo  
**Research:** Knowly AI, Promptcraft, Querri, Sequirly, Scira AI  
**Design:** Chronicle  
**Productivity:** Crystal, Dokie AI, Fern, Genspark AI, Happenstance, Slidescript  
**AI Automation:** Computer X, Flowstep, Lindy AI, Tanka  
**Project Management:** Portals  
**Resume & Career:** Huntr AI Resume  
**No-Code:** Bubble Mobile, Shipable AI  
**Security:** Emotion Sense Pro, Oblitaratus

---

## 🛠️ Tech Stack

| Layer | Technology | Purpose |
|-------|-----------|---------|
| **Frontend** | HTML5 + CSS3 + Vanilla JS | Single-file architecture, zero dependencies |
| **Icons** | Lucide Icons (jsDelivr CDN) | Theme-aware SVG icons (~30KB) |
| **Storage** | LocalStorage | Theme preference, visit tracking |
| **PWA** | Service Worker + Manifest | Offline support, installable app |
| **Hosting** | Netlify | Global CDN, auto-deploy |
| **Analytics** | Google Analytics (optional) | Usage tracking |

---

## 📦 Installation

### Option 1: Use Live Version
Visit [try-free-ai-tools-hub.netlify.app](https://try-free-ai-tools-hub.netlify.app)

### Option 2: Deploy Your Own

#### Deploy to Netlify (Recommended)
1. Fork or download this repository
2. Drag `ai-tools-hub-complete.html` to [app.netlify.com/drop](https://app.netlify.com/drop)
3. Rename to `index.html`
4. Upload `manifest.json`, `service-worker.js`, and `icon.svg`
5. Done! Your site is live on Netlify's global CDN

#### Local Development
```bash
# No build process needed - just open the file!
open ai-tools-hub-complete.html

# Or serve with any static server
python -m http.server 8000
# Visit http://localhost:8000
```

---

## 📱 PWA Setup

### Files Required
- `manifest.json` - App metadata, icons, theme colors
- `service-worker.js` - Offline caching, performance
- `icon.svg` - App icon (purple gradient robot theme)
- `icon-192.png` - 192x192 PNG icon (generated from SVG)
- `icon-512.png` - 512x512 PNG icon (generated from SVG)

### Installation Steps
1. Add manifest link to HTML `<head>`:
```html
<link rel="manifest" href="/manifest.json">
```

2. Register service worker before closing `</body>`:
```html
<script>
if('serviceWorker' in navigator){
  navigator.serviceWorker.register('/service-worker.js')
    .then(()=>console.log('SW registered'))
    .catch(err=>console.log('SW failed',err));
}
</script>
```

3. Generate PNG icons from SVG:
```bash
# Using ImageMagick or online converter
# Convert icon.svg to 192x192 and 512x512 PNG
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
    tags: ["Free Tier"],
    new: true  // Shows "New" badge
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
- ✅ **Free tier with meaningful functionality** (minimum 30-day access)
- ✅ **OR completely free forever** with no paid tiers
- ✅ **No credit card required** for free tier signup
- ✅ **Active development** and regular updates
- ✅ **Positive user reviews** and adoption
- ✅ **Clear value proposition** and use cases

---

## 🤝 Contributing

Want to suggest a tool? Open an issue with:
- Tool name and URL
- Description (1-2 sentences)
- Category fit
- Proof of free tier (screenshot or link to pricing)

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 👨‍💻 Built By

**Farman J** - AI Generalist  
- Portfolio: [farman024.github.io/Farman-J](https://farman024.github.io/Farman-J)
- Twitter: [@Farman__24__](https://twitter.com/Farman__24__)
- Website: [try-free-ai-tools-hub.netlify.app](https://try-free-ai-tools-hub.netlify.app)

---

## 🌟 Acknowledgments

Built with:
- [Lucide Icons](https://lucide.dev) - Beautiful SVG icons
- [Netlify](https://netlify.com) - Hosting and CDN
- Inspiration from the AI community

---

## 📈 Roadmap

### Phase 1: Q2 2026
- [ ] Expand to 150+ tools
- [ ] Add user ratings system
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

**Star ⭐ this repo if you find it useful!**

**[Visit AI Tools Hub →](https://try-free-ai-tools-hub.netlify.app)**
