# OussemaABDELMOULA.com — Personal Portfolio

> Static single-page portfolio for **Oussema ABDELMOULA** — Telecommunications Engineer and Data Scientist based in Paris, France. Built on the [iPortfolio](https://bootstrapmade.com/iportfolio-bootstrap-portfolio-websites-template/) Bootstrap template.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.0-7952B3?logo=bootstrap&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

---

## Overview

A lightweight, single-page personal website used as an online CV and project showcase. The site targets recruiters and hiring managers in the French tech market and is organised around five sections: Home, About, Resume, Projects, Contact.

The site is **100% static** — no back-end, no database. All vendor libraries (Bootstrap, AOS, Typed.js, Swiper, GLightbox, Boxicons) are loaded from public CDNs at runtime.

## Tech Stack

| Layer | Technologies |
|---|---|
| Markup | HTML5 |
| Styling | CSS3, Bootstrap 5, Bootstrap Icons, Boxicons |
| Interactions | Vanilla JavaScript, jQuery, AOS (Animate-On-Scroll), Typed.js, Swiper, GLightbox |
| Template base | iPortfolio (BootstrapMade) |
| Hosting | Static hosting (GitHub Pages / Netlify / Vercel compatible) |

## Project Structure

```
.
└── CV-OussemaAbdelmoula/
    ├── index.html              # single-page site
    ├── css/
    │   └── style.css           # custom theme on top of iPortfolio
    ├── js/
    │   └── main.js             # nav, scroll, Typed effect, AOS, skills animation
    ├── img/                    # profile picture, favicons, hero background
    ├── resume/
    │   └── CV-Oussema-Abdelmoula.pdf
    └── vendor/                 # local copies of Bootstrap / AOS / Swiper / … (unused — CDN preferred)
```

## Running Locally

No build step required. Any static HTTP server works:

```bash
# Python
cd CV-OussemaAbdelmoula
python -m http.server 8080
# open http://localhost:8080
```

```bash
# Node (npx)
npx serve CV-OussemaAbdelmoula
```

## Deployment

The site can be deployed to any static host:

- **GitHub Pages** — push to `gh-pages` or enable Pages on the `main` branch
- **Netlify / Vercel** — connect the repo, no build command needed
- **Apache / Nginx** — serve the `CV-OussemaAbdelmoula/` folder as the web root

The production site is available at **[OussemaABDELMOULA.com](https://www.OussemaABDELMOULA.com)**.

## Sections

1. **Home** — hero with animated typed roles
2. **About** — profile summary, contact coordinates, current focus
3. **Resume** — education, experience, certifications, social activities
4. **Projects** — featured work (see GitHub for the full list)
5. **Contact** — email, LinkedIn, GitHub

## Roadmap

- [x] Update the Projects section with the current repositories (Deep Learning / BI / others)
- [x] Add Data Engineering, Cybersecurity and DevOps skills to the Skills bar
- [x] Add SEO meta tags
- [ ] Swap CDN-loaded vendor libraries for the committed local copies, or remove `vendor/` entirely
- [ ] Add a screenshot of the rendered site at `docs/images/site_preview.png`
- [ ] Add Open Graph and Twitter cards
- [ ] Add a dark mode toggle
- [ ] Deploy a CI preview on every push (Netlify deploy previews)

## Author

**Oussema ABDELMOULA** — Telecommunications Engineer (ENET'COM, Tunisia) + M2 Data Science (Université Claude Bernard Lyon 1). Based in Paris, France.

- LinkedIn: [oussema-abdelmoula](https://www.linkedin.com/in/oussema-abdelmoula/)
- GitHub: [@oussemaenet](https://github.com/oussemaenet)
- Website: [OussemaABDELMOULA.com](https://www.OussemaABDELMOULA.com)
- Email: oussema.abdelmoula@gmail.com

## Credits

Built on the **iPortfolio** template by [BootstrapMade](https://bootstrapmade.com/iportfolio-bootstrap-portfolio-websites-template/).

## License

Released under the MIT License — see the [`LICENSE`](./LICENSE) file for details.
