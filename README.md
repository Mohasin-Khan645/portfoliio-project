# Portfolio Site

A responsive, modern portfolio website with three pages: `index.html`, `about.html`, and `contact.html`. It features a consistent navigation bar, mobile hamburger menu, and a dark, elegant theme using CSS variables, Flexbox, and Grid.

## Features
- Responsive layout with mobile hamburger navigation
- Modern dark theme using CSS custom properties
- Flexbox/Grid-based sections
- Accessible form styles on Contact page

## Project Structure
```
portfolio-site/
├── index.html
├── about.html
├── contact.html
├── styles/
│   └── main.css
├── images/
│   └── profile-pic.png
└── README.md
```

## Local Development
Open `index.html` directly in your browser, or use a static server for best results:

### Using VS Code Live Server
1. Install the Live Server extension
2. Right-click `index.html` → "Open with Live Server"

### Using Python (any OS)
```bash
python -m http.server 8000
```
Then visit `http://localhost:8000`.

## Deployment
This is a static site; deploy anywhere that serves static files:
- GitHub Pages
- Netlify
- Vercel
- Cloudflare Pages

### GitHub Pages (quick guide)
1. Commit and push the repository
2. In GitHub → Settings → Pages → Deploy from branch → `main` → `/ (root)`
3. Save; your site will be available at `https://<username>.github.io/<repo>`

## Customize
- Update `styles/main.css` theme variables under `:root`
- Replace `images/profile-pic.png`
- Edit copy in `index.html`, `about.html`, and `contact.html`


