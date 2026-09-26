# Interactive Portrait Scroll (Fairy in the Painting) 🌸

[![GitHub Pages](https://img.shields.io/badge/Demo-Live%20on%20GitHub%20Pages-f472b6?style=for-the-badge&logo=github)](https://abc15018045126.github.io/girl.github.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-amber.svg?style=for-the-badge)](LICENSE)

An elegant, interactive single-page application (SPA) designed as an artistic portrait scroll. It presents an evocative portrait of beauty and temperament, weaving together classical literary aesthetics, data visualization, tabbed exploration, and AI-powered literary generation.

🌐 **Live Demo:** [https://abc15018045126.github.io/girl.github.io/](https://abc15018045126.github.io/girl.github.io/)

---

## ✨ Features

- **🌐 Full Bilingual Experience**: Built-in support for **English (default)** and **Chinese (中文)** with a seamless one-click language switcher and persisted preferences.
- **📜 Classical Aesthetic Typography**: Sophisticated typography pairing *Playfair Display* and *Noto Serif SC* on a gentle, warm peach-rose backdrop.
- **📊 Temperament Radar Visualization**: Interactive multi-dimensional radar chart powered by **Chart.js**, translating abstract virtues (*Elegance, Composure, Gentleness, Vitality, Wisdom, Kindness*) into tangible metrics with interactive hover tooltips.
- **🗂 Granular Detail Explorer**: Interactive tabbed navigation to delve into individual facets of beauty (*Aura & Demeanor, Gaze & Expression, Face & Silhouette, Radiant Smile*).
- **✨ AI-Powered Literary Generation (Gemini 2.0)**:
  - **Poetic Interpretation**: Distills the subject's harmony of inner and outer grace into a poem or prose vignette.
  - **Detail Expansion**: Generates rich, evocative textual expansions for individual nuances.
  - *Includes curated poetic presets as graceful fallbacks when an API key is not configured.*

---

## 🛠 Tech Stack

- **Markup & Logic**: HTML5, Vanilla JavaScript (ES6+)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) + Custom CSS animations and glassmorphic components
- **Visualization**: [Chart.js](https://www.chartjs.org/)
- **Typography**: [Google Fonts](https://fonts.google.com/) (*Playfair Display*, *Noto Serif SC*, *Plus Jakarta Sans*)
- **AI Integration**: [Google Gemini API](https://ai.google.dev/) (`gemini-2.0-flash`)

---

## 🚀 Quick Start

### 1. View Directly
This is a static web application requiring no compilation or complex dependencies. Simply double-click `index.html` in your browser, or visit the [GitHub Pages link](https://abc15018045126.github.io/girl.github.io/).

### 2. Run Locally with a Development Server
You can serve the directory using Python or Node.js:

```bash
# Using Python 3
python -m http.server 8000

# Or using npx serve
npx serve .
```
Then navigate to `http://localhost:8000` in your web browser.

---

## 🔑 Optional: Configuring Gemini API Key

To enable real-time dynamic AI generation via Gemini:
1. Obtain an API key from [Google AI Studio](https://aistudio.google.com/).
2. In `index.html`, locate the `GEMINI_API_KEY` configuration constant and set your key:
   ```javascript
   const GEMINI_API_KEY = "YOUR_API_KEY_HERE";
   ```
*(Note: If no API key is set, the application provides built-in poetic fallbacks so all UI interactions remain functional).*

---

## 📄 License

This project is licensed under the terms of the [MIT License](LICENSE).
