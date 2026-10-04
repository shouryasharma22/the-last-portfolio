# The Last Portfolio

**Live site:** https://shouryasharma-lastportfolio.onrender.com/

A personal portfolio for **Shourya Sharma**, a Computer Science & Engineering student at NITK Surathkal and full-stack developer. Built for the *Silicon Maze: The Last Portfolio* challenge.

## Concept

The site is a recovered archive from the Avengers: Doomsday timeline: a surviving record kept by someone who made it through the Incursions. Instead of a loud sci-fi dashboard, the Doomsday theme comes from restraint and atmosphere:

- A near-black, green-tinted palette with a single tarnished Doom-green accent
- Editorial serif typography (EB Garamond) paired with a quiet sans (Hanken Grotesk) and small monospace labels (JetBrains Mono)
- Generous empty space, hairline dividers, and a faint film-grain overlay
- Faded, desaturated atmospheric background plates behind sections
- Copy written in the archive's voice: Latveria, Doomstadt, Incursions, and a few lines of Doom speaking in the third person

The Marvel references are textual and atmospheric only. No official logos, posters or artwork are used.

## Sections

| Section | What it shows |
|---|---|
| Survivor identified (hero) | Name, role, short introduction and portrait |
| 01 The survivor's log | About me, the story behind Semexam, and key facts |
| 02 The arsenal | Skills grouped into Languages, Frontend, Backend & Data, and Tools |
| 03 The archives | Featured projects with description, tech used, preview image and live link |
| 04 The final transmission | Email, LinkedIn and GitHub links |

## Projects featured

- **Semexam** (https://semexam.vercel.app): a college resource platform for NITK students, with notes, past papers and academic material. React, Node.js, Express, MongoDB and the Google Drive API, with server-side pagination and optimized search.
- **Community Watch** (https://community-watch-hazel.vercel.app): a Codeforces anti-cheating and verification platform that uses the Codeforces API to detect, verify and report suspicious submissions.

## Features

- Fully responsive layout, designed for desktop and mobile
- Fixed navigation with smooth scrolling to each section
- Portrait hero that sits beside the text on desktop and above it on mobile, so it never overlaps the navigation or content
- Subtle hover states: underline reveals, accent colour shifts and image emphasis
- Respects `prefers-reduced-motion`
- No build step and no dependencies to install

## Tech stack

- HTML5
- Tailwind CSS (via CDN) with a custom theme configuration
- Vanilla JavaScript for navigation
- Google Fonts: EB Garamond, Hanken Grotesk, JetBrains Mono

The initial layout was drafted with Google Stitch and then adapted for this project.

## Run locally

This is a single static page.

1. Download the project folder (it contains `index.html` and the portrait image).
2. Open `index.html` in a browser, or serve the folder with the VS Code Live Server extension.

An internet connection is needed for the Tailwind CDN and Google Fonts.

## Customisation

- **Portrait framing:** change the `--portrait-pos` value in the `.hero-portrait` rule near the top of `index.html` (format: `x% y%`) to move the focal point.
- **Content:** all text lives directly in `index.html`, section by section.
- **Colours and fonts:** edit the `tailwind.config` block in the `<head>`.

## Deployment

Hosted on Render as a static site: https://shouryasharma-lastportfolio.onrender.com/

## Contact

- Email: shouryasharma1203@gmail.com
- LinkedIn: https://linkedin.com/in/shourya-sharma-65bb99396
- GitHub: https://github.com/shouryasharma22

*End of transmission. Doom is inevitable. So is shipping.*
