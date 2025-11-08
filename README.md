# Compendium: Neurotransmitters & Psychophysiology

[![GitHub license](https://img.shields.io/badge/license-Unlicense-blue.svg)](https://unlicense.org/)
[![GitHub issues](https://img.shields.io/github/issues/fabianzimber/hormone-compendium.svg)](https://github.com/fabianzimber/hormone-compendium/issues)
[![GitHub stars](https://img.shields.io/github/stars/fabianzimber/hormone-compendium.svg)](https://github.com/fabianzimber/hormone-compendium/stargazers)

An interactive one-page website that provides a compendium on neurotransmitters (dopamine, norepinephrine, serotonin, and melatonin) and their role in psychophysiology. The page analyzes symptoms of deficiency/excess, core functions, interactions, and systemic connections to disorders such as depression, ADHD, and PTSD. Developed as a responsive, accessible tool for educational purposes.

**Live Demo:** [Open the Page]([https://yourusername.github.io/yourrepo/](https://fabianzimber.github.io/hormone-compendium/)) 

## Description

This website is an educational compendium that illuminates the central neurotransmitters of the brain. It integrates scientific sources with interactive elements such as a heatmap for transmitter effects, multilingual support (DE/EN), and customizable difficulty levels (simple/advanced). Topics include:

- Symptoms of deficiency, core functions, and hyperactivity for each transmitter.
- An interactive heatmap to visualize effects on systems like mood, drive, sleep, etc.
- Systemic analyses of disorders (e.g., HPA axis in depression, phase delay in ADHD).
- Citation references with tooltips for sources (based on peer-reviewed studies).

The page is designed as a "one-pager" – everything in one HTML file, ideal for GitHub Pages or quick deployment.

## Features

- **Multilingual & Multi-Level:** Switch between German/English and simple/advanced language levels for broad accessibility.
- **Interactive Heatmap:** Visualizes transmitter effects with D3.js; colors and values adapt to the theme.
- **Accordion Elements:** Expandable sections for detailed analyses of disorders.
- **Citation Tooltips:** Hover effects for source links that are evidence-based (e.g., from PubMed, Nature, PMC).
- **Responsive Design:** Mobile-friendly with Tailwind CSS; grid layout for cards and heatmap.
- **No Dependencies Beyond CDNs:** No build tools needed – runs directly in the browser.

## Prerequisites

- None – the page is static and runs in any modern browser.
- For local development: A web browser (e.g., Chrome, Firefox).

## Installation & Setup

1. Clone the repository:
> git clone https://github.com/yourusername/yourrepo.git
2. Open `index.html` in your browser.
3. (Optional) Deploy to GitHub Pages:
- Go to Repository Settings > Pages.
- Select the `main` branch and save.

No further dependencies – all libraries (Tailwind, D3.js, Inter Font) are loaded via CDN.

## Usage

- **Switch Language:** Click on DE/EN in the header.
- **Difficulty Level:** Choose "Advanced" or "Simple".
- **Switch Theme:** Click on the icons (sun/moon/contrast) in the header (not visible in code, but expandable).
- **Explore Heatmap:** The matrix shows effect strengths (-2 to +2); hover for details (CSS-based).
- **Check Sources:** Hover over cited terms for tooltips with links.

Example: Switch to "Dark Theme" for better readability in low light.

## Technologies

- **HTML5 & CSS3:** Structure and styling with CSS variables for theming.
- **Tailwind CSS:** Utility-first CSS for responsive design (via CDN).
- **D3.js:** For dynamic heatmap generation (via CDN).
- **JavaScript:** Event listeners for switches (language, level, theme) and local storage (localStorage for theme).
- **Fonts:** Inter via CDN for modern typography.
- **Accessibility:** ARIA attributes implicit (expandable), High-Contrast mode.

## Contribution

Contributions are welcome! Follow these steps:

1. Fork the repository.
2. Create a branch: `git checkout -b feature/your-feature`.
3. Commit your changes: `git commit -m 'Description'`.
4. Push: `git push origin feature/your-feature`.
5. Create a Pull Request.

Please ensure clean code, source citations, and accessibility.

## License

This project is licensed under the Unlicense – see the file for details.

## Acknowledgments

- Based on evidence-based sources from PubMed, Nature, PMC, etc.
- Inspired by modern psychoneurobiological models.
- Created with ❤️ for education and science.

If you have questions, open an issue or contact me!
