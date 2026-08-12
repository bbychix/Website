# Chikomborero Chimuka — Portfolio

Personal portfolio site. Software developer and digital systems specialist based
in Harare, Zimbabwe.

**Live:** https://bbychix.github.io/Website/

## About

A single-page scroll-driven portfolio covering background, skills, interests,
projects, work experience and certifications. No framework, no build step.

## Contents

| Section | What's in it |
|---|---|
| Hero | Full-bleed video, interactive name |
| About | Background and approach |
| Skills | Six areas of technical practice |
| Beyond the screen | Chess, piano, cooking, cycling, painting |
| Projects | Four selected builds |
| Experience | Three roles, plus education |
| Certificates | Ten certifications, viewable in full |
| Contact | Details, CV download, message form |

## Features

- Scroll-driven hero: video loads only when in view, still frame shown first
- Procedurally rendered 3D gear mechanism on canvas, cursor-reactive
- Certificates stack like an iOS app switcher, expand to a grid
- 3D tilt on skill and project cards
- Text that types itself out as you scroll
- Responsive across desktop, tablet and mobile
- Respects `prefers-reduced-motion`
- Images below the fold are lazy-loaded

## Built with

HTML, CSS and vanilla JavaScript. Archivo and JetBrains Mono via Google Fonts.

## Structure

```
index.html      the page
support.js      runtime, required
assets/
  img/          portrait, hobbies, backgrounds
  certs/        ten certificate scans
  hero-eye.mp4  hero video
  hero-eye-poster.jpg
  Chikomborero-Chimuka-CV.pdf
.nojekyll       stops GitHub Pages preprocessing the files
```

Keep the structure intact — paths are relative.

## Running locally

Serve the folder rather than opening `index.html` directly, so the browser
allows the local file requests:

```
python3 -m http.server
```

Then visit http://localhost:8000

## Deploying to GitHub Pages

1. Push the contents of this folder to the repository root
2. Settings → Pages → Source: deploy from `main`, folder `/ (root)`
3. Save, then wait a minute for the first build

## Contact

- Email: chikoc2000@gmail.com
- GitHub: [@bbychix](https://github.com/bbychix)
- Location: Harare, Zimbabwe

Open to roles, freelance briefs and collaborations.
