# Glimpse Website

Landing page for the Glimpse micro-journal iOS app.

## Setup

### Required Images

Add the following images to the `images/` folder:

1. **app-logo.png** - Your Glimpse app icon (recommended: 512x512 or larger)

2. **screenshot-1.jpeg** - Home screen / main journal view
3. **screenshot-2.jpeg** - Insights screen
4. **screenshot-3.jpeg** - Light and dark mode comparison
5. **screenshot-4.jpeg** - Entry composition screen
6. **screenshot-5.jpeg** - PDF export screen
7. **screenshot-6.jpeg** - Privacy lock screen

The screenshots are already in place with device frames and star backgrounds.

### App Store Link

Replace the placeholder `href="#"` links with your actual App Store URL once available. Search for these in `index.html`:

```html
<a href="#" class="app-store-btn
```

There are 3 App Store button links to update.

## Deployment to GitHub Pages

1. Create a new repository on GitHub
2. Push this folder to the repository
3. Go to Settings > Pages
4. Select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Your site will be live at `https://yourusername.github.io/repository-name`

### Custom Domain

1. In your domain registrar, add a CNAME record pointing to `yourusername.github.io`
2. In GitHub Pages settings, enter your custom domain
3. Enable "Enforce HTTPS"

## File Structure

```
/
├── index.html      # Main landing page
├── privacy.html    # Privacy policy
├── images/
│   ├── app-logo.png
│   ├── screenshot-1.jpeg
│   ├── screenshot-2.jpeg
│   ├── screenshot-3.jpeg
│   ├── screenshot-4.jpeg
│   ├── screenshot-5.jpeg
│   └── screenshot-6.jpeg
└── README.md
```

## Tech Stack

- Plain HTML
- Tailwind CSS (via CDN)
- Google Fonts (Nunito)
- No build process required
