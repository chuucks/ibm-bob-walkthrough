# IBM Bob — Technical Walkthrough Presentation

An interactive, lightweight, and responsive single-page HTML presentation detailing the engineering paradigms, capabilities, and configurations of **IBM Bob (AI Software Development Lifecycle Partner)**.

This walkthrough is based on official developer guidelines and Carlos Salazar's technical overview presentation: *"Software Engineering Practice in the age of AI Coding"*.

👉 **View the Live Presentation on GitHub Pages:** **[https://chuucks.github.io/ibm-bob-walkthrough/](https://chuucks.github.io/ibm-bob-walkthrough/)**

---

## 🚀 Key Features

* **Carbon-Inspired UI**: Handcrafted, lightweight CSS using official IBM Carbon Design System tokens, typography styles, and responsive spacing grids. No bulky framework dependencies!
* **Home Page Mascot & Widget**: Displays the official companion mascot (`Bob_image.png`) with an interactive speech bubble cycling through **8 authentic, documentation-validated tips** on context management, security controls, and prompt priorities.
* **Vertical Side-Menu Navigation**: Smooth, instant tab switching that keeps content lightweight and automatically resets viewport scroll heights.
* **Dual Theme Toggle**: Supports full **Light Mode** and **Dark Mode** (toggled in the top-right corner) with persistent CSS custom properties.
* **GitHub Pages Ready**: Self-contained architecture optimized for instant, zero-build deployment.

---

## 📂 Repository File Guide

* **[`index.html`](index.html)**: The primary monolithic entry point holding the HTML markup, CSS stylesheet, and vanilla JavaScript switching logic.
* **[`Bob_image.png`](Bob_image.png)**: The official Bob mascot companion icon.
* **[`PLAN.md`](PLAN.md)**: Topic grouping mapping and development roadmap.
* **[`AGENTS.md`](AGENTS.md)**: Workspace context rules for AI assistant productivity.
* **[`.bob/`](.bob/)**: Config directories for mode-specific guidelines (`rules-agent`, `rules-ask`, and `rules-plan`).
* **[`.bobignore`](.bobignore)**: Access privilege boundaries preventing Bob from reading or modifying sensitive system secrets.
* **[`.gitignore`](.gitignore)**: Excludes local OS cache files and workspace system debug logs.

---

## 💻 Local Quick Start

To preview and interact with the presentation locally on your machine, simply execute the following command in your terminal:

```bash
open index.html
```

This starts your native default web browser instantly, requiring no local server or packaging configurations!
