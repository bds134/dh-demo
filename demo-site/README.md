# Redlining and Urban Space

**HIST 501D Digital History — Binghamton University — Spring 2026**

A small static digital history site examining the relationship between 1930s HOLC neighborhood grading boundaries and present-day income disparities.

## Live Site

[https://bds134.github.io/dh-demo/demo-site/index.html](https://bds134.github.io/dh-demo/demo-site/index.html)

## Repository Contents

```
index.html            Home page — project overview and research question
planning.html         Interface sketches and design decisions
findings.html         Featured artifact and interpretation
sustainability.html   Platform documentation and preservation notes
style.css             Stylesheet
assets/
  holc-map.png        Map artifact (HOLC grades + 2020 census income)
  sketch-home.jpg     Interface sketch — home page
  sketch-findings.jpg Interface sketch — findings page
  sketch-sustainability.jpg  Interface sketch — sustainability page
```

## Data Sources

- **HOLC boundary data:** [Mapping Inequality](https://dsl.richmond.edu/panorama/redlining/), University of Richmond Digital Scholarship Lab
- **Census income data:** U.S. Census Bureau, American Community Survey 5-Year Estimates (2020), retrieved via Census API

The Python script used to produce the map is at `scripts/make-holc-map.py` in the main course repository.

## How to View Locally

Open any `.html` file directly in a browser. No build step or local server is required.

## How to Deploy

This site is hosted via GitHub Pages. To enable:

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Set source to the `main` branch, root folder
4. The live URL will appear at `https://bds134.github.io/dh-demo/demo-site/index.html`

## Course Context

This repository is the demo site for the Week 9/10 GitHub Pages workshop. It demonstrates the required four-page structure: Home, Planning, Findings, and Sustainability.

Student projects with specific needs and a well-defined product do not need to follow this template exactly — that is fine. What matters is that the site is **simple, static, and well documented**. Whatever structure you choose, your site should include a **planning page** (design decisions, interface sketches, research question) and a **sustainability page** (platform documentation, data sources, preservation notes) for now. These pages stand in for a methods page and a site documentation page that have not yet been developed for the course; once those page types are defined, the planning and sustainability pages can be retired or repurposed.

See the assignment description in the course repository for full requirements.
