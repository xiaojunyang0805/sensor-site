# Sensor.SeeNano.nl - Research Portfolio

**Biosensor research portfolio for Xiaojun Yang**

## About

Simple single-page site showcasing:
- Research background
- Technical expertise
- Publications (add your actual publications)
- Collaboration opportunities

## Tech Stack

- HTML5
- Tailwind CSS (via CDN)
- Static site (no build process)

## Local Development

Open `index.html` in browser or use simple server:

```bash
python -m http.server 8000
```

## Deployment

Deploy to Cloudflare Pages as separate project:

1. Create GitHub repo: `sensor-site`
2. Push code
3. Create new Cloudflare Pages project
4. Connect repo
5. Add custom domain: `sensor.seenano.nl`

## Customization

### Add Your Publications:

Edit the "Selected Publications" section in `index.html`:

```html
<div class="border-l-4 border-blue-500 pl-6 py-2">
    <p class="font-medium text-lg mb-1 text-gray-900">
        Your Publication Title
    </p>
    <p class="text-gray-600 text-sm mb-2">
        Authors: Yang, X., et al.
    </p>
    <p class="text-gray-500 text-sm">
        Journal of Biosensors, 10(5), 123-145, 2024
    </p>
</div>
```

### Add CV Download:

1. Upload CV PDF to your server
2. Update CV link in HTML:
   ```html
   <a href="/path/to/your-cv.pdf" download>Download CV</a>
   ```

## Contact

xiaojun@seenano.nl
