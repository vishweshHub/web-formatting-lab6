# Cosmic Odyssey - Web Formatting Lab 6

A modern, responsive web page demonstrating advanced web styling using **external CSS**. Showcases background image integration, harmonious text color palettes, and multiple creative techniques for styling text borders.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Responsive Design](https://img.shields.io/badge/Responsive-Design-00f2fe?style=for-the-badge)

---

## 🌟 Features

### 1. Background Image with External CSS
- **Layered Gradient Vignette**: Blends dark linear gradients over a high-resolution cosmic wallpaper for high legibility.
- **Fixed Parallax**: Configured with `background-attachment: fixed` and `background-size: cover` for dynamic visual depth during scroll.
- **Glassmorphic Cards**: Content panels utilize `backdrop-filter: blur(16px)` and translucent surfaces so the cosmic imagery subtly peeks through.

### 2. Text Color Palette System
- Defined via CSS Custom Properties (`--color-cyan`, `--color-amber`, `--color-magenta`, etc.).
- **Gradient-Clipped Text**: Uses `background: linear-gradient(...)` with `-webkit-background-clip: text` and transparent fill for iridescent headlines.
- **Neon Text Shadows**: Multi-layered `text-shadow` creating a subtle luminous effect against dark backgrounds.
- **Modern Typography**: Incorporates Google Fonts (`Outfit` and `Space Grotesk`) with `text-wrap: balance` on headings and `text-wrap: pretty` on paragraphs.

### 3. Text Border Techniques
Demonstrates 6 distinct methods to style borders on and around text elements:
1. **Character Stroke / Hollow Outline**: Uses `-webkit-text-stroke: 1.5px #38ef7d` with transparent text fill.
2. **Solid Neon Pill**: Bordered badge with `border: 2px solid #00f2fe` and full pill radius.
3. **Dashed Frame**: Cyberpunk-style technical label framed with `border: 2px dashed #f6d365`.
4. **Double Border Plaque**: Regal multi-stroke title framed with `border: 4px double #e056fd`.
5. **Asymmetric Left Border**: Editorial callout quote with `border-left: 4px solid #4facfe`.
6. **Animated Shimmering Gradient Border**: Multi-color linear gradient wrapper highlighting important labels.

---

## 📁 Project Structure

```
.
├── index.html            # Semantic HTML5 markup
├── style.css             # External CSS stylesheet with design tokens & styling
├── images/
│   └── background.jpg    # Cosmic nebula background image
└── README.md             # Project documentation
```

---

## 🚀 Getting Started

To view the page locally:

1. Clone this repository:
   ```bash
   git clone https://github.com/vishweshHub/web-formatting-lab6.git
   cd web-formatting-lab6
   ```

2. Open `index.html` in your browser, or start a local server:
   ```bash
   python3 -m http.server 3000
   ```

3. Visit `http://localhost:3000` in any modern web browser.

---

## 📄 License
MIT License. Created for Web Technologies Lab 6.
