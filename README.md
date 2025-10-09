<h1 align="center">Jiacheng Dong — Academic Homepage</h1>

<p align="center">
Modern, responsive academic homepage powered by Jekyll (Minimal Mistakes based).
</p>

<!-- <p align="center">
  <img src="docs/screenshot.png" width="100%"/>
</p> -->

## Overview

This repository hosts the source code of my personal academic homepage. It is built on top of the Minimal Mistakes theme and the "AcadHomepage" starter, with custom sections for publications, news, projects, honors, education, and internships.

Live site: https://djctionary.github.io/

## Quick Start

1) Prerequisites

- Ruby, RubyGems, GCC, Make
- Bundler (optional but recommended)

2) Run locally

```bash
bash run_server.sh
# then open http://127.0.0.1:4000
```

3) Deploy

Push to the `main` branch. GitHub Pages will publish to `https://<USERNAME>.github.io`.

## Customize

- Profile and socials: `_config.yml` under `author:`
  - Name, avatar: `images/Jiacheng_Dong.jpg`
  - Location, email, Google Scholar, LinkedIn, GitHub
- About page contents: `_pages/about.md`
  - Bio, news, publications (with cover images), honors, education, internships
  - Projects: links to Palm Stream and Skinova
- Images: place under `images/` (e.g., `PPHA.jpg`, `MPDD.png`, `HGF-MiLaG.png`)
- Styles: `assets/css/main.scss`
  - You can add custom background (e.g., `images/background.svg`) and tweak layout styles

## Publications Section

Each paper uses a "paper-box" card composed of an image (cover) and text. See `_pages/about.md` for examples of how to add a new entry with badge, cover and links.

## Google Scholar Badges (Optional)

This template supports Google Scholar citation badges via a GitHub Action and the `google_scholar_stats_use_cdn` setting. Configure your `GOOGLE_SCHOLAR_ID` secret and the action will generate stats files automatically.

## Project Structure

```
assets/           # CSS/JS and vendor files
images/           # avatars, icons, publication covers, background
_pages/           # page markdown (about page lives here)
_includes/        # theme partials
_layouts/         # base layout
_sass/            # SCSS partials (theme styles)
_site/            # generated site (do not edit)
```

## Acknowledgements

- Minimal Mistakes by Michael Rose
- AcadHomepage starter by Raye Ren

## License

This repository inherits licenses of its upstream theme/components. Content you add (text, images, code snippets) is your own unless otherwise stated.