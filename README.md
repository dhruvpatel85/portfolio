# Dhruv Patel — Frontend Developer Portfolio

Multi-page personal portfolio with a light theme and a dark-mode toggle.

**Role**: Frontend Developer | B.Tech CSE Student  
**Location**: Valsad  
**Status**: Open to Frontend Development Internships

## Structure

```
portfolio/
├── index.html      # Home: hero + featured projects
├── about.html      # Bio, skills (grouped), experience
├── projects.html   # Full project showcase
├── contact.html    # Contact links
├── styles.css      # Shared styles (light + dark themes)
├── script.js       # Theme toggle + mobile menu
├── images/         # Project screenshots and skill icons (keep your existing folder)
└── README.md
```

## How to view

1. Open `index.html` in any modern browser.
2. Or serve locally:

```bash
python -m http.server 8000
# Visit http://localhost:8000
```

## Customizing

- Colors and fonts are CSS variables at the top of `styles.css`.
- The dark theme is the `:root[data-theme='dark']` block.
- The code window in the hero is plain HTML in `index.html`; edit the lines to change what it shows.

## Details included

- **Email**: dhruvvpatel85@gmail.com
- **GitHub**: https://github.com/dhruvpatel85
- **LinkedIn**: https://www.linkedin.com/in/dhruv-patel-a21107290
- **Projects**: Komal RO, Leaf Analyzer, Fitness Planner

## Deployment

Free options: GitHub Pages, Netlify (drag and drop the folder), Vercel, Cloudflare Pages.
Upload the entire `portfolio` folder, including `images/`.
