# PALAPALLE LOKESH — Agentic World Portfolio

> Personal portfolio of **Palapalle Lokesh** — Java Backend Developer | Agentic AI | n8n Automation | GCP & AWS

**Live Site:** [lokesh-palaplle-18.github.io/Lokesh-portfolio](https://lokesh-palaplle-18.github.io/Lokesh-portfolio/)

---

## What's Inside

A fully interactive 3D portfolio built with Three.js, WebGL shaders, and Tailwind CSS — **no frameworks, no build tools, single HTML file.**

### Features
- 10-layer Three.js 3D scene (galaxy spiral, DNA helix, nebula, wireframe spheres, orbiting nodes)
- WebGL aurora shader background
- Custom cursor with canvas trail + spring-physics blob
- Matrix rain canvas overlay
- Bento grid + Glassmorphism dark UI
- Typing animation cycling through roles
- Interactive Tech Dependency Graph (Canvas 2D, hover to inspect nodes)
- Technical Proficiency skill bars with animated fill
- Radar/Spider chart with **click-to-compare** mode
- GitHub Activity Graph (animated contribution heatmap)
- Live IST Clock badge in hero
- Scroll progress ring around back-to-top button
- 3D CSS carousel for projects with hover tech-stack overlay
- Achievement badges that unlock on scroll
- Sound visualizer equalizer bars on sound toggle
- Copy contact button with toast notification
- Education timeline with learning journey
- Terminal easter egg (press backtick `` ` ``)
- Dark/Light mode toggle
- Confetti burst
- Magnetic buttons
- Parallax scroll effects
- Preloader with boot animation
- Responsive layout

---

## Tech Stack

| Technology | Version | Purpose |
|---|---|---|
| **Three.js** | r128 | 3D WebGL scene — galaxy, helix, torus rings, orbiting nodes |
| **WebGL / ShaderMaterial** | — | Aurora shader background effect |
| **Canvas 2D API** | — | Tech node graph, radar chart, activity graph, cursor trail, matrix rain |
| **Tailwind CSS** | CDN v3 | Utility-first responsive styling |
| **CSS 3D Transforms** | — | Project carousel (rotateY + translateZ perspective) |
| **IntersectionObserver API** | — | Scroll-triggered animations, skill bars, achievement badges |
| **Web Audio API** | — | Synthesized sound effects |
| **Clipboard API** | — | Copy contact number feature |
| **Font Awesome** | 6.4.0 | Icons throughout |
| **Google Fonts** | — | JetBrains Mono, Inter, Space Grotesk |
| **Vanilla JavaScript** | ES2020+ | All interactivity — no frameworks |
| **HTML5 / CSS3** | — | Single-file architecture |

---

## Run Locally

### Option 1 — Open Directly (No Setup)

```bash
# macOS
open index.html

# Windows
start index.html

# Linux
xdg-open index.html
```

### Option 2 — Local Dev Server (Recommended)

```bash
# Python (built-in, no install needed)
python3 -m http.server 7777
# Open: http://localhost:7777/index.html

# Node.js
npx serve .
# Open: http://localhost:3000

# VS Code → Install "Live Server" extension
# Right-click index.html → Open with Live Server
```

---

## Deploy for Free

### 1. GitHub Pages (Easiest — Recommended)

**Cost: Free | Custom domain: Yes | CDN: Yes**

1. Push your code to GitHub
2. Go to repo → **Settings → Pages**
3. Source: `Deploy from a branch`
4. Branch: `main` | Folder: `/ (root)` → **Save**
5. Wait ~2 minutes

**Live URL:**
```
https://lokesh-palaplle-18.github.io/Lokesh-portfolio/
```

---

### 2. Netlify (Drag & Drop — 1 Minute)

**Cost: Free | 100GB bandwidth/month | Custom domain: Yes**

**Option A — Drag & Drop:**
1. Go to [netlify.com](https://netlify.com) → Sign up free
2. Drag your project folder onto the Netlify dashboard
3. Done — live instantly with a random URL like `https://amazing-name-123.netlify.app`

**Option B — Connect GitHub:**
1. Netlify → **Add new site → Import from Git**
2. Connect your GitHub repo `Lokesh-portfolio`
3. Build command: *(leave empty)*
4. Publish directory: `.` (root)
5. Deploy — auto-deploys on every push

```bash
# Or via Netlify CLI
npm install -g netlify-cli
netlify deploy --prod --dir .
```

---

### 3. Vercel (GitHub Auto-Deploy)

**Cost: Free | Global CDN | Custom domain: Yes**

1. Go to [vercel.com](https://vercel.com) → Sign up with GitHub
2. Click **New Project → Import** your `Lokesh-portfolio` repo
3. Framework: **Other**
4. Root directory: `.`
5. Click **Deploy**

**Live URL:**
```
https://lokesh-portfolio.vercel.app
```

Every `git push` auto-deploys. No setup needed after first deploy.

---

### 4. Cloudflare Pages (Fastest CDN — Free)

**Cost: Free | Unlimited bandwidth | 500 builds/month**

1. Go to [pages.cloudflare.com](https://pages.cloudflare.com)
2. **Create a project → Connect to Git**
3. Select your `Lokesh-portfolio` repo
4. Build command: *(leave empty)*
5. Build output directory: `/`
6. Deploy

**Live URL:**
```
https://lokesh-portfolio.pages.dev
```

---

### 5. Render (Cost-Effective Full Stack Option)

**Cost: Free static sites | No sleep time**

1. Go to [render.com](https://render.com) → Sign up
2. **New → Static Site**
3. Connect GitHub repo
4. Build command: *(leave empty)*
5. Publish directory: `.`
6. Deploy

---

## Deployment Comparison

| Platform | Cost | Custom Domain | Auto-Deploy | CDN | Best For |
|---|---|---|---|---|---|
| GitHub Pages | Free | Yes (free) | On push | Yes | Simplest setup |
| Netlify | Free tier | Yes (free) | On push | Yes | Drag & drop speed |
| Vercel | Free tier | Yes (free) | On push | Yes | Best performance |
| Cloudflare Pages | Free | Yes (free) | On push | Global | Fastest CDN |
| Render | Free | Yes | On push | Yes | Full-stack later |

**Recommendation:** Use **GitHub Pages** now (already configured), switch to **Vercel or Netlify** when you want a custom domain.

---

## Latest Updates (v3.0)

### New Features Added
- GitHub Activity Graph with animated reveal
- Live IST Clock badge in hero section
- Scroll progress ring around back-to-top button
- Sound visualizer equalizer (animated bars on toggle)
- Project card hover overlay showing tech stack
- Copy contact button with toast notification
- Radar chart click-to-compare mode (select 2 skills)
- Achievement badges unlocking on scroll through sections
- Cursor blob with spring physics trailing effect

### Fixes
- Tech Dependency Graph node labels — increased font, added dark pill background + glow
- Technical Proficiency skill bar labels — white text, colored percentages
- Radar/Spider chart labels — larger font, pill background, extended canvas to 360x360
- Education timeline dates corrected (2021–2025 degree, 2026 onwards for learning)

---

## Project Structure

```
Lokesh-portfolio/
├── index.html          # Complete portfolio (single file)
├── README.md           # This file
└── graphic-designer-portfolio.html   # Alternate design variant
```

---

## Contact

- **GitHub:** [github.com/lokesh-palaplle-18](https://github.com/lokesh-palaplle-18)
- **LinkedIn:** [linkedin.com/in/palapalle-lokesh-458a81448](https://www.linkedin.com/in/palapalle-lokesh-458a81448/)
- **Phone:** +91 9490233047
- **Location:** India
