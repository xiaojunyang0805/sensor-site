# Sensor.SeeNano.nl - Biosensor Research Portfolio

**Professional research and hardware portfolio for Xiaojun Yang**

Live site: [sensor.seenano.nl](https://sensor.seenano.nl)

## About

Comprehensive single-page research portfolio showcasing:
- **4 Current Research Projects** (€80K funded)
- **Real Publications** (JACS 2020, Analytical Chemistry 2022)
- **Hardware Platforms** (Potentiostat, Electrodes, Wearable Dev-Kit)
- **Machine Learning Project** (StepReaderCNN-MVP)
- **Research Posters** (including 2024 Prize Winner)
- **Collaboration Opportunities** (Academic, Industry, Hardware, Students)
- **Contact Form** (Popup modal with Formspree integration)

## Key Features

✅ **Real Research Content** - No placeholders or fake information
- Saxion University Applied Nanotechnology work (2022-2025)
- 2 peer-reviewed journal publications with DOIs
- 2024 Dutch Micro-Nano Conference Poster Prize
- €40K KIEM-GoChem funding (2 projects)

✅ **Hardware Sales Integration**
- Point-of-Need Potentiostat (€199)
- Functional Electrodes (€20/electrode)
- Wearable Dev-Kit (€249, in development)
- Popup contact form for inquiries

✅ **Research Projects**
1. Micro-/Nanoparticle Sizing (€40K, 2024-2025)
2. MIP-Based PFAS Sensor
3. SporeSpotter (€40K, 2025-2026)
4. ORCHIDD Project (ECsens collaboration)

✅ **Interactive Elements**
- View Poster buttons (3 PDF posters included)
- Machine Learning demo links (GitHub + Streamlit)
- Popup contact form with product selector
- Responsive design (mobile-first)

## Tech Stack

- **HTML5** - Semantic markup
- **Tailwind CSS** (via CDN) - Utility-first styling
- **Vanilla JavaScript** - Modal functionality
- **Formspree** - Form submissions (free tier)
- **Static Site** - No build process required

## Repository Structure

```
sensor-site/
├── index.html                                           # Main site
├── README.md                                            # This file
├── 20240117 Poster_single-Entity Electrochemistry.pdf  # Research poster
├── 20241021 Poster_MNP sizer_v03.pdf                   # Prize-winning poster
└── 250925 Poster_MIP enabled PFAS sensor_v1.pdf        # PFAS sensor poster
```

## Local Development

### Option 1: Direct File Open
```bash
# Simply open in browser
open index.html  # macOS
start index.html # Windows
xdg-open index.html # Linux
```

### Option 2: Python Server
```bash
cd sensor-site
python -m http.server 8000
# Open http://localhost:8000
```

### Option 3: VS Code Live Server
1. Install "Live Server" extension
2. Right-click `index.html`
3. Select "Open with Live Server"

## Deployment

### Deployed on Cloudflare Pages

**Current Setup:**
- GitHub Repo: `xiaojunyang0805/sensor-site`
- Auto-deploy on push to `main` branch
- Custom Domain: `sensor.seenano.nl`

**Deployment Steps:**
1. Push changes to GitHub: `git push`
2. Cloudflare Pages auto-deploys (1-2 minutes)
3. Changes live at sensor.seenano.nl

**Cloudflare Pages Settings:**
- Build command: (empty)
- Build output directory: `/`
- Root directory: (empty)

### Manual Deployment to Other Platforms

#### Netlify:
```bash
# Install Netlify CLI
npm install -g netlify-cli

# Deploy
netlify deploy --prod
```

#### GitHub Pages:
1. Settings → Pages
2. Source: Deploy from branch
3. Branch: `main`, folder: `/`

#### Vercel:
```bash
vercel --prod
```

## Content Management

### Update Publications
Edit the "Peer-Reviewed Publications" section in `index.html` (lines ~397-484)

### Update Research Projects
Edit the "Current Research Projects" section (lines ~83-200)

### Update Hardware Pricing
Edit the "Hardware & Technology Platforms" section (lines ~203-273)

### Add New Posters
1. Add PDF to repository root
2. Add "View Poster" button with link to PDF
3. Commit and push

### Update Contact Email
Current email: `xiaojunyang0805@gmail.com`
- Update in contact form (line ~671)
- Update in footer (line ~715)

### Formspree Configuration
Form endpoint: `https://formspree.io/f/xanyqgqv`
- Submissions sent to: xiaojunyang0805@gmail.com
- Free tier: 50 submissions/month
- To change: Create new Formspree form and update action URL

## Customization Guide

### Colors
Main colors used:
- Blue: `#2563eb` (primary buttons)
- Green: `#16a34a` (success badges)
- Purple: `#9333ea` (gradients)
- Orange: `#ea580c` (poster prize)

### Fonts
Uses system fonts via Tailwind:
```css
font-family: ui-sans-serif, system-ui, sans-serif
```

### Add New Section
```html
<section class="mb-20">
    <h2 class="text-4xl font-bold mb-4 text-center">Section Title</h2>
    <p class="text-gray-600 text-center mb-12 text-lg">Subtitle</p>
    <!-- Your content here -->
</section>
```

## Performance

- ⚡ First Contentful Paint: <1s
- 📱 Mobile-friendly (responsive design)
- 🎨 No external dependencies except Tailwind CSS CDN
- 📦 Total size: ~4.5MB (includes 3 PDF posters)
- 🚀 Lighthouse Score: 95+ expected

## SEO

Optimized meta tags:
- Title: "Biosensor Research & Hardware | Xiaojun Yang"
- Description: Electrochemical biosensor research and hardware development
- Keywords: biosensor, electrochemical sensing, MIP sensor, PFAS detection
- Open Graph tags for social sharing

## Browser Support

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## Recent Updates (Nov 2025)

### Major Changes:
1. ✅ Replaced all placeholder content with real research data
2. ✅ Added 2 peer-reviewed publications (JACS 2020, Analytical Chemistry 2022)
3. ✅ Added 4 current research projects with funding details
4. ✅ Added hardware platforms with pricing
5. ✅ Added Machine Learning project (StepReaderCNN-MVP)
6. ✅ Added 3 research poster PDFs with view buttons
7. ✅ Converted contact form to popup modal
8. ✅ Updated contact information to Gmail
9. ✅ Changed title from "PhD Researcher" to "NanoSensor Researcher"
10. ✅ Updated work timeline to 2022-2025

### Bug Fixes:
- Fixed LinkedIn URL to correct profile
- Removed fake credentials
- Updated all email addresses

## Contact

**Email:** xiaojunyang0805@gmail.com
**LinkedIn:** [linkedin.com/in/xiaojun-yang-5066b0114](https://www.linkedin.com/in/xiaojun-yang-5066b0114)
**GitHub:** [github.com/xiaojunyang0805](https://github.com/xiaojunyang0805)
**Twitter:** [@XiaojunYang0805](https://twitter.com/XiaojunYang0805)

## License

© 2025 SeeNano Technology BV. All rights reserved.

## Credits

Built with assistance from Claude Code (Anthropic).
