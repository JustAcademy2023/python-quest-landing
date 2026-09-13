# Python Quest Landing

A single page, board game themed landing page for **"Python Certification Guide: Which Certificate Boosts Your Career in 2026?"**. Built as a static site, ready to deploy on GitHub Pages with zero build step.

## Concept

Instead of a standard SaaS card layout, the page frames your python certification journey as a snake and ladder style board game. A vertical trail of numbered tiles runs from Start Square through Python Fundamentals, up a ladder at PCEP, past a trap square that represents skipping structured learning, up another ladder at PCAP, and finally into the Career Square. Below the board, learners pick a character class (Analyst, Builder, Tester, or a bonus MERN quest) and compare Solo Mode self study against Multiplayer Mode live training.

## Features

- Fully responsive layout, from a four column desktop grid down to a single column mobile trail
- A custom zig zag game board path built with layered CSS and color coded ladder and trap tiles
- Four character class cards linking to real course, bootcamp, and roadmap pages
- A solo mode versus multiplayer mode comparison section reframing live interactive, instructor led, and mentor led training as a play style choice
- Accessible focus states, semantic headings, and a native `details` and `summary` powered FAQ section that needs no JavaScript
- Eight fully clickable links woven through the header, hero, board, character cards, CTA banner, and footer
- Zero dependencies beyond Google Fonts, no build tools, no frameworks

## Tech stack

Plain HTML, CSS, and a few lines of vanilla JavaScript for the mobile menu, all in a single `index.html` file. Fonts loaded from Google Fonts: Baloo 2 for playful display headings, Inter for body copy, and JetBrains Mono for tile numbers and tags.

## Run locally

Clone the repository and open `index.html` directly in a browser, or serve it locally:

```bash
git clone https://github.com/your-username/python-quest-landing.git
cd python-quest-landing
python3 -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

## Deploy on GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, set the source to **Deploy from a branch**.
4. Select the `main` branch and the `/root` folder, then save.
5. GitHub will publish the page at `https://your-username.github.io/python-quest-landing/`.

## Project structure

```
python-quest-landing/
├── index.html
└── README.md
```

## Links used on this page

- Python course in Pune
- Data analytics bootcamp in Pune
- MERN stack developer bootcamp in Pune
- Selenium training in Pune
- Python certification guide (main topic blog)
- Python training and certification blog
- MERN stack developer roadmap 2026 blog
- Full stack python developer roadmap 2026 blog
