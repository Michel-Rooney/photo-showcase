# Photo Showcase

[HTML5](https://developer.mozilla.org/en-US/docs/Web/HTML) [CSS3](https://developer.mozilla.org/en-US/docs/Web/CSS) [GitHub Pages](https://pages.github.com/)

A simple, accessible photo gallery built with semantic HTML and CSS as part of the [roadmap.sh](https://roadmap.sh/) frontend learning path.

[Live website](https://michel-rooney.github.io/photo-showcase/) | [Project brief](https://roadmap.sh/projects/photo-showcase)

## Overview

Photo Showcase demonstrates how to describe images with useful alternative text, add captions with `figure` and `figcaption`, and embed a video with native browser controls and fallback content.

## Features

- Semantic `header`, `main`, and `footer` page structure
- Six images with alternative text and explicit dimensions
- Captions for the gallery photos and a decorative image skipped by screen readers
- Embedded video with controls, a poster image, and fallback text
- Responsive media sizing and static deployment through GitHub Pages

## Built With

- HTML5
- CSS3
- GitHub Pages
- GitHub Actions

## Project Structure

```text
.
|-- index.html
|-- README.md
|-- .github
|   `-- workflows
|       `-- deploy.yml
`-- src
    |-- css
    |   `-- style.css
    |-- img
    `-- media
        `-- videoplayback.mp4
```

## Links

- [Live website](https://michel-rooney.github.io/photo-showcase/)
- [GitHub repository](https://github.com/Michel-Rooney/photo-showcase)
- [roadmap.sh project](https://roadmap.sh/projects/photo-showcase)

## Local Development

Open `index.html` in a browser, or start a local static server:

```bash
python3 -m http.server
```

Then visit `http://localhost:8000`.
