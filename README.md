# 🍓 Les Fruités - Training Academy Landing Page

> A responsive landing page for "Les Fruités" - 2026 intensive training academy for fruity drinks & desserts

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## 📋 About

Complete **single-page landing website** for "Les Fruités," a training academy offering intensive courses on creating and selling fruity drinks and desserts. Features modern design, smooth animations, responsive layout, and integrated Airtable registration form.

### Key Features

| Feature | Description |
|---------|-------------|
| 🎨 Modern Design | Fresh green-yellow color scheme matching fruity brand |
| 📱 Fully Responsive | Optimized for mobile, tablet, desktop |
| ✨ Smooth Animations | Fade-down animations and hover effects |
| 📝 Registration Form | Embedded Airtable form for sign-ups |
| 💳 Payment Info | Western Union & Mixx by Yas details |
| 🔄 Single-Page Nav | Smooth home/form page transitions |

## 🚀 Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom styling with CSS variables, gradients, animations
- **Vanilla JavaScript** - Page transitions and interactivity
- **Google Fonts** - Playfair Display & Nunito typography
- **Airtable** - Registration form backend (embedded) 
- **GitHub Pages** - Free hosting

## 📂 Project Structure

## 🎯 Features

### Homepage Sections

1. **Hero** - Animated badge, headline with emojis, welcome text, circular logo
2. **Key Info Cards** - Date, format, type, certificate, follow-up, contact
3. **Training Modules** - 5 modules (desserts, juices, sales, equipment, follow-up)
4. **Pricing** - 50,000 FCFA with payment methods (Western Union, Mixx by Yas)
5. **How It Works** - 3-step process (Register → Pay → Join Google Meet)
6. **CTA** - "S'inscrire à la Formation" button with blue gradient

### Form Page

- Top bar with "Retour" button
- Payment reminder with numbered steps
- Embedded Airtable registration form (620px height)

## 🛠️ Installation

### Local Development

```bash
git clone https://github.com/yourusername/les-frutes-landing-page.git
cd les-frutes-landing-page
python -m http.server 8000
# Open http://localhost:8000
```

### GitHub Pages

```bash
# 1. Create repository on GitHub
# 2. Push your files
git add index.html images/logo.jpg README.md
git commit -m "Initial commit"
git push origin main

# 3. Enable GitHub Pages: Settings > Pages > Source: main branch
```

Live at: `https://yourusername.github.io/les-frutes-landing-page/`

## 🎨 Design System

### Color Palette

```css
:root {
  --green:  #2d7a1f;    /* Primary green */
  --green2: #4caf2a;    /* Secondary green */
  --red:    #c0392b;    /* Accent red */
  --yellow: #f9c923;    /* Highlight yellow */
  --cream:  #fffbea;    /* Background cream */
  --dark:   #1a1a1a;    /* Text dark */
  --white:  #ffffff;    /* White */
}
```

### Typography

| Element | Font | Weight |
|---------|------|--------|
| Headings | Playfair Display | 700, 900 |
| Body | Nunito | 400, 600, 700, 800 |

## 📱 Responsive

```css
@media (max-width: 600px) {
  .iframe-wrapper iframe { height: 700px; }
  .form-page-header { padding: 24px 18px; }
}
```

## 🔗 External Integrations

| Service | Purpose |
|---------|---------|
| Airtable | Registration form |
| Google Fonts | Typography |
| WhatsApp | Payment confirmation (+228 90 27 00 80) |
| Google Meet | Training delivery |

## 📞 Contact

- **Phone/WhatsApp:** +228 90 27 00 80
- **Location:** Lomé, Maritime, Togo
- **Training:** 10-14 March 2026
- **Price:** 50,000 FCFA



## 🙏 Acknowledgments

- Google Fonts (Playfair Display, Nunito)
- Airtable (embeddable form)
- GitHub Pages (free hosting)

---

**Built with ❤️ by Sanders POTOPAWI** | *May 2026*
