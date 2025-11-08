# Compendium: Neurotransmitters & Psychophysiology

[![GitHub license](https://img.shields.io/badge/license-Unlicense-blue.svg)](https://unlicense.org/)
[![GitHub issues](https://img.shields.io/github/issues/abianzimber/know-your-hormones.svg)](https://github.com/fabianzimber/know-your-hormones/issues)
[![GitHub stars](https://img.shields.io/github/stars/abianzimber/know-your-hormones.svg)](https://github.com/abianzimber/know-your-hormones/stargazers)

An interactive one-page website that provides a compendium on neurotransmitters (dopamine, norepinephrine, serotonin, and melatonin) and their role in psychophysiology. The page analyzes symptoms of deficiency/excess, core functions, interactions, and systemic connections to disorders such as depression, ADHD, and PTSD. Developed as a responsive, accessible tool for educational purposes.

**Live Demo:** [Open the Page](https://yourusername.github.io/yourrepo/) (replace with your GitHub Pages URL).

## Description

This website is an educational compendium that illuminates the central neurotransmitters of the brain. It integrates scientific sources with interactive elements such as a heatmap for transmitter effects, multilingual support (DE/EN), and customizable difficulty levels (simple/advanced). Topics include:

- Symptoms of deficiency, core functions, and hyperactivity for each transmitter.
- An interactive heatmap to visualize effects on systems like mood, drive, sleep, etc.
- Systemic analyses of disorders (e.g., HPA axis in depression, phase delay in ADHD).
- Citation references with tooltips for sources (based on peer-reviewed studies).

The page is designed as a "one-pager" – everything in one HTML file, ideal for GitHub Pages or quick deployment.

## Features

- **Multilingual & Multi-Level:** Switch between German/English and simple/advanced language levels for broad accessibility.
- **Theme Support:** Light, Dark, and High-Contrast modes for accessibility (WCAG-compliant, implemented with CSS variables).
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
