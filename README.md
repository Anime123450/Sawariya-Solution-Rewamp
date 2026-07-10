# Sawariya Solution 🦚

A responsive, multi-page company website for **Sawariya Solution** — a web & mobile app development company based in Vadodara, Gujarat, India.

I built this as part of my software development internship. My mentor asked me to put together a complete, modern marketing website for the company using plain front-end technologies (no CMS, no page builder) and take it all the way to a working live link. This repo is the result.

🔗 **Live site:** https://anime123450.github.io/Sawariya-Solution-Rewamp/

![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?logo=jquery&logoColor=white)
![GitHub Pages](https://img.shields.io/badge/Deployed-GitHub%20Pages-222?logo=github)

---

## 📖 About the project

The brief from my mentor was simple to say but had a lot in it: *"build the company site, keep it consistent, keep it clean, and get it live."*

So the whole thing is static — just **HTML, CSS and JavaScript** — which keeps it fast, easy to host, and dependency-free. There's no backend and no build step; what you see in the repo is exactly what ships.

Some of the things I focused on while building it:

- **One consistent header and footer on every page** so navigation feels the same no matter where you land.
- **A single font family across the whole site** (Jost) for a clean, uniform look.
- **Fully responsive** layouts that hold up from large desktops down to phones.
- **Self-hosted fonts and assets** so nothing depends on an external font service loading.
- Getting it **live on GitHub Pages** and making sure every internal link, image and asset resolves correctly on the hosted subpath.

## ✨ Features

- 🖥️ **Modern, animated landing page** with a dark hero section and gradient accents
- 🧭 **Sticky navigation** that stays pinned while you scroll
- 📱 **Responsive design** — mobile, tablet and desktop
- 🗂️ **Large multi-page site** — home, about, services, case studies, blog, contact, plus dedicated service/technology landing pages
- 💬 **Get-a-Quote / contact forms** and a floating WhatsApp button
- 🔤 **Self-hosted Jost webfont** + Font Awesome icons
- 🔎 **SEO-friendly** — meta tags, Open Graph tags, favicon and a web app manifest
- 🍪 Cookie-consent notice
- 🎨 Consistent Sawariya Solution branding (logo, colours, contact details) throughout

## 🛠️ Built with

| Area | Tech |
|------|------|
| Markup | HTML5 |
| Styling | CSS3 (custom, media queries, flexbox & grid) |
| Interactivity | Vanilla JavaScript + jQuery |
| Icons | Font Awesome |
| Typography | Jost (self-hosted webfont) |
| Hosting | GitHub Pages |

## 📁 Project structure

```
Sawariya-Solution-Rewamp/
├── index.html                 # Home page
├── about-us/                  # About page
├── services/                  # Services overview
├── contact-us/                # Contact page
├── case-study/                # Case studies
├── blog/                      # Blog
├── ...                        # service & technology landing pages
├── wp-content/
│   ├── themes/nbt/            # CSS, JavaScript and fonts
│   └── uploads/               # images, logo and media
├── favicon.ico                # site favicon (peacock mark)
├── site.webmanifest           # PWA / web app manifest
└── README.md
```

Each page lives in its own folder with an `index.html`, which gives clean URLs like `/about-us/` and `/services/`.

## 🚀 Running it locally

The easiest way to see it is the **[live link](https://anime123450.github.io/Sawariya-Solution-Rewamp/)**.

To run it on your own machine, the internal paths are set up for the `/Sawariya-Solution-Rewamp/` base, so serve it from the **parent** of the project folder:

```bash
# 1. clone the repo (keep the folder name as-is)
git clone https://github.com/Anime123450/Sawariya-Solution-Rewamp.git

# 2. from the folder that CONTAINS Sawariya-Solution-Rewamp, start any static server, e.g.
python -m http.server 8000
#   or:  npx serve
#   or:  php -S localhost:8000

# 3. open
http://localhost:8000/Sawariya-Solution-Rewamp/
```

> Tip: opening `index.html` straight from the file system won't load the styles, because the site uses absolute paths — it needs to be served over `http://`.

## 🌐 Deployment

The site is deployed with **GitHub Pages** from the `main` branch (root folder). Every push to `main` automatically rebuilds and publishes the live site. A `.nojekyll` file is included so Pages serves the files exactly as they are.

## 📄 Main pages

| Page | Path |
|------|------|
| Home | `/` |
| About Us | `/about-us/` |
| Services | `/services/` |
| Case Studies | `/case-study/` |
| Blog | `/blog/` |
| Contact | `/contact-us/` |

...along with a large set of individual service and technology landing pages.

## 🙏 Acknowledgements

Big thanks to my internship mentor for the guidance, the design feedback, and for reviewing the work along the way. A lot of the polish — consistent header/footer, unified typography, and the smaller CSS fixes — came directly from that feedback.

## 👤 Author

**Animesh Sharma**
GitHub: [@Anime123450](https://github.com/Anime123450)

---

<sub>Built during my internship • Sawariya Solution • Vadodara, Gujarat</sub>
