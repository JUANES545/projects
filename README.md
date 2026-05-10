<div align="center">

# Studio

**Juan Mejía — Native · Backend · Web**

[![HTML](https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white)]()
[![CSS](https://img.shields.io/badge/CSS-1572B6?style=flat-square&logo=css3&logoColor=white)]()
[![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=three.js&logoColor=white)]()
[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-222?style=flat-square&logo=github&logoColor=white)](https://juanes545.github.io/studio/)

---

[Live site](https://juanes545.github.io/studio/)

</div>

Personal brand page and app downloads hub. Showcases projects and Android apps built by Juan Mejía — Android & software developer focused on tools that blur the line between software and hardware.

## Tech stack

- Plain HTML + CSS + JavaScript — single file (`index.html`)
- [Three.js r128](https://threejs.org/) via CDN for the animated particle background
- Hosted on GitHub Pages

## Run locally

```bash
open index.html
```

No build step, no server, no dependencies to install.

## Add a project card

Copy an existing `.card` block inside the Projects grid and update the `href`, emoji, title, description, and tags.

## Add an app card

Copy an existing `.app-card` block inside the Apps grid. Set the download link to:

```
https://github.com/JUANES545/<repo>/releases/latest
```

## Deploy

```bash
git checkout master
git merge develop
git push
```

GitHub Pages publishes automatically within ~1 minute after every push to `master`.
