# Jemima Renovates — Website Tracker

## Status: Live (content being added)

**Live URL:** https://shetlandj.github.io/jemima_renovates/
**Domain:** jemimarenovates.co.uk (DNS not yet configured)
**Hosting:** GitHub Pages (Actions workflow)
**Tech:** Static HTML/CSS/JS (same approach as Park Circus Dream House)

## Pages

| Page | File | Status |
|---|---|---|
| Homepage | `index.html` | Live — 4 project cards, hero, about teaser |
| About | `about.html` | Live — real bio, stats, testimonials, services |
| Projects | `projects.html` | Live — 4 project cards |
| Contact | `contact.html` | Live — email, Instagram, YouTube |
| East End | `projects/east-end.html` | Live — full case study + gallery |
| City Centre | `projects/city-centre.html` | Live — full case study + gallery |
| Southside | `projects/southside.html` | Live — 9-photo gallery, Jan 2025 renovation |
| Craigpark | `projects/craigpark.html` | Live — basic page, needs more content/photos |
| Project template | `projects/example-project.html` | Template for future pages |

## Project Card Order

1. Craigpark
2. East End
3. City Centre
4. Southside

## Design

- **Palette:** Cream `#E8DCC8`, black `#1a1a1a`, charcoal `#333`, brown accent `#8B7355`
- **Fonts:** DM Serif Display (headings) + Inter (body) via Google Fonts
- **Style:** Bold editorial — full-bleed heroes, high contrast
- **Deliberately different** from Steph's site (soft/warm/centered vs bold/editorial/wide)

## Still To Do

- [ ] Configure custom domain DNS (jemimarenovates.co.uk)
- [ ] More content/photos for Craigpark project page
- [ ] Confirm email address (currently `hello@jemimarenovates.co.uk`)
- [ ] Generate proper `favicon.ico` from the SVG
- [ ] Set up Git LFS for large images
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
├── images/
│   ├── hero.jpg, jay.jpg, aberfeldy-lounge.jpg, argyle-st-*.jpg
│   ├── craigpark-1.jpg, craigpark-2.jpg
│   ├── about-wide.jpg, contact-hero.jpg, projects-hero.jpg
│   └── southside/          (9 photos: pic1-pic9.jpg)
├── projects/
│   ├── east-end.html
│   ├── city-centre.html
│   ├── southside.html
│   ├── craigpark.html
│   └── example-project.html
├── logo.jpg
├── favicon.svg
├── sitemap.xml
├── robots.txt
├── .github/workflows/pages.yml
└── .gitignore
```

## Notes

- Lightbox JS (`js/lightbox.js`) — keyboard nav, touch swipe, ARIA labels
- GitHub Pages workflow includes LFS checkout
- Nav/footer duplicated per page (no build step)
- CSS cache-busted with `?v=4` query string
- Bio/testimonials sourced from kelvingrovepropertysourcing.com
- Southside photos by Amy @a.creative__
