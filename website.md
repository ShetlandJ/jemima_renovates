# Jemima Renovates — Website Tracker

## Status: Scaffolded (placeholder content)

**Domain:** jemimarenovates.co.uk
**Hosting:** GitHub Pages
**Tech:** Static HTML/CSS/JS (same approach as Park Circus Dream House)

## Pages

| Page | File | Status |
|---|---|---|
| Homepage | `index.html` | Built — placeholder projects |
| About | `about.html` | Built — placeholder bio & images |
| Projects | `projects.html` | Built — placeholder cards |
| Project template | `projects/example-project.html` | Built — template with lightbox |
| Contact | `contact.html` | Built — placeholder email/socials |

## Design

- **Palette:** Cream `#E8DCC8`, black `#1a1a1a`, charcoal `#333`, brown accent `#8B7355`
- **Fonts:** DM Serif Display (headings) + Inter (body) via Google Fonts
- **Style:** Bold editorial — full-bleed heroes, asymmetric grids, high contrast
- **Deliberately different** from Steph's site (soft/warm/centered vs bold/editorial/wide)

## Still To Do

- [ ] Get real project photos from Jemima
- [ ] Replace all placeholder images (`images/hero.jpg`, `images/about-placeholder.jpg`, etc.)
- [ ] Replace placeholder project cards with real projects
- [ ] Confirm email address (currently `hello@jemimarenovates.co.uk`)
- [ ] Confirm Instagram handle (currently `@jemimarenovates`)
- [ ] Get/confirm bio text from Jemima
- [ ] Add real testimonials (if available)
- [ ] Generate `favicon.ico` from the SVG
- [ ] Set up Git LFS for project images (`brew install git-lfs`)
- [ ] Create GitHub repo and push
- [ ] Configure custom domain DNS
- [ ] Test responsive layout at all breakpoints
- [ ] Validate HTML / check accessibility
- [ ] Add any additional social links (TikTok, etc.)

## File Structure

```
jemima_renovates/
├── index.html
├── about.html
├── projects.html
├── contact.html
├── css/main.css
├── js/lightbox.js
├── images/              (placeholder — needs real images)
├── projects/
│   └── example-project.html  (template)
├── logo.jpg
├── favicon.svg
├── CNAME
├── sitemap.xml
├── robots.txt
├── .github/workflows/pages.yml
└── .gitignore
```

## Notes

- Lightbox JS (`js/lightbox.js`) adapted from proven pattern — keyboard nav, touch swipe, ARIA labels
- GitHub Pages workflow includes LFS checkout for when we add large images
- Each project page follows the template in `projects/example-project.html`
- Nav/footer are duplicated per page (no build step) — same approach as Steph's site
