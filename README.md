# Hizkia Letwar — Personal Portfolio

> **"Elegance Is My Philosophy"**

A modern, elegant, and fully responsive single-page portfolio website built with pure HTML, CSS, and JavaScript. Designed with a mobile-first approach and featuring smooth animations, lazy loading, and accessibility best practices.

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

---

## 📋 Table of Contents

- [About](#-about)
- [Features](#-features)
- [Tech Stack](#-tech-stack)
- [Design Philosophy](#-design-philosophy)
- [Sections Overview](#-sections-overview)
- [Getting Started](#-getting-started)
- [File Structure](#-file-structure)
- [Customization](#-customization)
- [Deployment](#-deployment)
- [Browser Compatibility](#-browser-compatibility)
- [Performance](#-performance)
- [Accessibility](#-accessibility)
- [Author](#-author)
- [License](#-license)

---

## 🙋‍♂️ About

This is the official personal portfolio website of **Hizkia Letwar**, a student at **SMK Negeri 1 Maluku Tengah** majoring in **Telecommunication and Computer Network Engineering (TJKT)** and serving as an **OSIS IT Department member**.

The website showcases a unique approach to web development called **"Vibe Coding"** — an AI-assisted development methodology where natural language ideas are transformed into functional code, allowing developers to focus on creativity and problem-solving.

### Key Highlights

| Aspect | Details |
|--------|---------|
| **Name** | Hizkia Letwar |
| **School** | SMK Negeri 1 Maluku Tengah |
| **Major** | TJKT (Telecommunication & Computer Network Engineering) |
| **Role** | OSIS IT Department Member |
| **Focus** | AI Engineering, Web Development |
| **Philosophy** | "Elegance Is My Philosophy" |
| **Development Style** | Vibe Coding (AI-Assisted) |

---

## ✨ Features

### Visual & Interactive

- 🎨 **Dark Theme** — Elegant black background with subtle gradient overlays
- 🌊 **Glassmorphism Navigation** — Frosted glass effect navbar with backdrop blur
- ⌨️ **Typewriter Effect** — Dynamic text cycling through multiple phrases
- 📱 **Fully Responsive** — Mobile-first design with breakpoints for all screen sizes
- 🎭 **Scroll Animations** — Smooth reveal animations as you scroll
- 🚀 **Lazy Loading** — Sections load progressively as they enter viewport
- 🎯 **Smooth Scrolling** — Native smooth scroll behavior
- 🔄 **Hover Effects** — Subtle transformations on interactive elements

### Navigation

- 📱 **Mobile Hamburger Menu** — Collapsible navigation for small screens
- 🔗 **Anchor Links** — Smooth scroll to sections (About, Projects, Tools, Contact)
- 📍 **Sticky Header** — Navigation bar with scroll-based visibility
- ♿ **ARIA Labels** — Full accessibility support for screen readers

### Performance

- ⚡ **Zero Dependencies** — No external frameworks or libraries (except fonts)
- 🎯 **Optimized CSS** — CSS custom properties for efficient theming
- 🧠 **Intersection Observer** — Efficient scroll-triggered animations
- 🚫 **Reduced Motion Support** — Respects user's motion preferences
- 📦 **Single File** — Everything in one HTML file for fast loading

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **HTML5** | Semantic structure and content |
| **CSS3** | Styling with custom properties, flexbox, grid |
| **JavaScript (Vanilla)** | Interactive features and animations |
| **Google Fonts** | Inter font family for typography |
| **SVG** | Inline icons and graphics |

### CSS Features Used

- **Custom Properties (CSS Variables)** — Centralized theming system
- **Flexbox** — Layout management
- **CSS Grid** — Complex grid layouts
- **Media Queries** — Responsive breakpoints
- **CSS Animations** — Keyframe animations
- **Transitions** — Smooth state changes
- **Backdrop Filter** — Glassmorphism effects
- **Transform** — 2D/3D transformations
- **Calc()** — Dynamic calculations

### JavaScript Features Used

- **Intersection Observer API** — Scroll-triggered animations
- **Request Animation Frame** — Smooth scroll handling
- **DOM Manipulation** — Dynamic content updates
- **Event Listeners** — User interaction handling
- **SetTimeout** — Typewriter effect timing
- **MatchMedia** — Reduced motion detection

---

## 🎨 Design Philosophy

### Core Principles

```
"Elegance Is My Philosophy"
```

The design is built around three core principles:

1. **Clean UI** — Minimalist design with purposeful elements
2. **Elegant Functions** — Every interaction feels smooth and intentional
3. **Thoughtful Features** — Each feature serves a clear purpose

### Color Palette

| Variable | Value | Usage |
|----------|-------|-------|
| `--bg` | `#000000` | Main background |
| `--bg-elevated` | `#0a0a0b` | Elevated surfaces |
| `--fg` | `#F5F5F7` | Primary text |
| `--fg-secondary` | `#d1d1d6` | Secondary text |
| `--muted` | `#86868b` | Muted text |
| `--muted-secondary` | `#6e6e73` | Deep muted text |
| `--accent` | `rgba(255, 255, 255, 0.04)` | Accent backgrounds |
| `--accent-hover` | `rgba(255, 255, 255, 0.08)` | Hover states |
| `--border` | `rgba(255, 255, 255, 0.06)` | Subtle borders |
| `--border-hover` | `rgba(255, 255, 255, 0.12)` | Hover borders |

### Typography Scale

| Variable | Mobile | Desktop |
|----------|--------|---------|
| `--text-xs` | 0.6875rem | 0.75rem |
| `--text-sm` | 0.8125rem | 0.875rem |
| `--text-base` | 0.9375rem | 1rem |
| `--text-lg` | 1.0625rem | 1.125rem |
| `--text-xl` | 1.125rem | 1.25rem |
| `--text-2xl` | 1.25rem | 1.75rem |
| `--text-3xl` | 1.75rem | 3rem |
| `--text-hero` | 2.25rem | 5rem |

### Spacing System

All spacing follows a consistent scale:

- `--space-xs`: 4px
- `--space-sm`: 8px
- `--space-md`: 16px
- `--space-lg`: 24px
- `--space-xl`: 32px
- `--space-2xl`: 48px
- `--space-3xl`: 64px
- `--space-4xl`: 96px

### Border Radius

- `--radius-xs`: 6px
- `--radius-sm`: 10px
- `--radius-md`: 14px
- `--radius-lg`: 20px
- `--radius-xl`: 28px

### Animation Timing

| Variable | Value | Usage |
|----------|-------|-------|
| `--duration-fast` | 150ms | Quick interactions |
| `--duration-base` | 250ms | Standard transitions |
| `--duration-slow` | 400ms | Smooth animations |
| `--duration-slower` | 600ms | Complex sequences |

**Easing Functions:**
- `--ease-out`: `cubic-bezier(0.16, 1, 0.3, 1)`
- `--ease-in-out`: `cubic-bezier(0.65, 0, 0.35, 1)`

---

## 📑 Sections Overview

### 1. Navigation
- Fixed position header with glassmorphism effect
- Logo (HL initials)
- Mobile hamburger menu
- Navigation links: About, Projects, Tools, Contact

### 2. Hero Section
- Overline text with decorative element
- Main title with animated span
- Typewriter effect with rotating phrases:
  - "Elegance Is My Philosophy"
  - "Vibe Coding Enthusiast"
  - "AI-Assisted Developer"
  - "Problem Solver"
  - "Future AI Engineer"
- Subtitle description
- CTA buttons: "Lihat Proyek" and "Hubungi Aku"
- Scroll indicator (desktop only)

### 3. Bio/About Section
- Two-column layout (desktop)
- Section label and heading
- Three paragraphs of biographical content
- Details grid with:
  - School
  - Major
  - Role
  - Focus area

### 4. Philosophy Section
- Centered quote card
- Gradient text effect
- Description text

### 5. Projects Section
- Section header
- Featured project card (SIRA - Sistem Informasi Razia Siswa)
  - Badge indicator
  - Title and subtitle
  - Description
  - Feature list with checkmarks
  - Technology tags
- Project grid with additional cards

### 6. Tools Section
- Grid layout of AI tools used:
  - Trae AI
  - ChatGPT
  - Gemini
  - Qwen
  - Qwen Code CLI

### 7. Inspiration Section
- Mentor card featuring "Pak Bahy"
- Avatar placeholder
- Name, role, and description

### 8. Contact Section
- Centered layout
- Title and description
- Email link with hover underline animation
- Social links:
  - GitHub (@Ikyletwar)
  - TikTok (@ikyletwar)
  - Instagram (@ikyletwar)

### 9. Footer
- Copyright text
- Philosophy tagline

---

## 🚀 Getting Started

### Prerequisites

This is a static website with no build process required. You only need:

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A text editor (optional, for customization)

### Installation

1. **Clone or download** this repository:
   ```bash
   git clone <repository-url>
   cd <project-folder>
   ```

2. **Open the file** in your browser:
   ```bash
   # On Windows
   start index.html

   # On macOS
   open index.html

   # On Linux
   xdg-open index.html
   ```

3. **Or use a local server** (recommended):
   ```bash
   # Using Python 3
   python -m http.server 8000

   # Using Node.js (npx)
   npx serve

   # Using PHP
   php -S localhost:8000
   ```

4. **Navigate to** `http://localhost:8000` in your browser

---

## 📁 File Structure

```
project-root/
│
├── index.html          # Main HTML file (contains all CSS and JS)
└── README.md           # This documentation file
```

### Inside index.html

```
index.html
│
├── <!DOCTYPE html>
├── <head>
│   ├── Meta tags
│   ├── Title
│   ├── Google Fonts links
│   └── <style> (CSS - ~1,400 lines)
│       ├── CSS Custom Properties
│       ├── Reset & Base Styles
│       ├── Background Effects
│       ├── Navigation Styles
│       ├── Section Styles
│       ├── Component Styles
│       ├── Animation Classes
│       └── Responsive Media Queries
│
├── <body>
│   ├── Background elements (gradient, noise)
│   ├── Content wrapper
│   │   ├── Navigation
│   │   ├── Main content
│   │   │   ├── Hero Section
│   │   │   ├── Bio Section
│   │   │   ├── Philosophy Section
│   │   │   ├── Projects Section
│   │   │   ├── Tools Section
│   │   │   ├── Inspiration Section
│   │   │   └── Contact Section
│   │   └── Footer
│   │
│   └── <script> (JavaScript - ~200 lines)
│       ├── Variable Initialization
│       ├── DOMContentLoaded Handler
│       ├── Mobile Navigation
│       ├── Scroll Reveal Animation
│       ├── Lazy Loading
│       ├── Nav Scroll Effect
│       └── Typewriter Effect
│
└── </body>
</html>
```

---

## 🔧 Customization

### Changing Personal Information

1. **Name and Title**
   - Search for "Hizkia Letwar" and replace with your name
   - Update the `<title>` tag

2. **Contact Information**
   - Email: Search for `manggadurian20@gmail.com`
   - Social links: Update `href` attributes in the social-links section

3. **Bio Content**
   - Edit paragraphs in the `.bio-content` section
   - Update details in `.detail-grid`

4. **Projects**
   - Modify project cards in the projects section
   - Update featured project information

### Changing Colors

Edit the CSS custom properties in the `:root` selector:

```css
:root {
    --bg: #000000;              /* Change background */
    --fg: #F5F5F7;              /* Change text color */
    --accent: rgba(255,255,255,0.04);  /* Change accent color */
}
```

### Changing Typography

Update the Google Fonts link and font-family:

```html
<!-- Change this link -->
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<!-- And update font-family in CSS -->
font-family: 'Your Font', sans-serif;
```

### Modifying Typewriter Texts

Find the `typewriterTexts` array in the JavaScript section:

```javascript
const typewriterTexts = [
    '"Elegance Is My Philosophy"',
    '"Vibe Coding Enthusiast"',
    '"AI-Assisted Developer"',
    '"Problem Solver"',
    '"Future AI Engineer"'
];
```

Replace with your own phrases.

### Adjusting Animation Speed

Modify the duration variables:

```css
:root {
    --duration-fast: 150ms;
    --duration-base: 250ms;
    --duration-slow: 400ms;
    --duration-slower: 600ms;
}
```

---

## 🌐 Deployment

This is a static website and can be deployed to any static hosting platform.

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to **Settings > Pages**
3. Select your branch and folder
4. Your site will be available at `https://username.github.io/repo-name`

### Vercel

1. Install Vercel CLI:
   ```bash
   npm i -g vercel
   ```

2. Deploy:
   ```bash
   vercel
   ```

3. Follow the prompts

### Netlify

1. Drag and drop your project folder to [Netlify Drop](https://app.netlify.com/drop)
2. Or connect your Git repository for automatic deployments

### Manual Hosting

Simply upload `index.html` to any web server or hosting provider.

---

## 🌍 Browser Compatibility

### Supported Browsers

| Browser | Version | Support |
|---------|---------|---------|
| Chrome | 80+ | ✅ Full |
| Firefox | 75+ | ✅ Full |
| Safari | 13+ | ✅ Full |
| Edge | 80+ | ✅ Full |
| Opera | 65+ | ✅ Full |
| Samsung Internet | 11+ | ✅ Full |

### Feature Support

| Feature | Support | Notes |
|---------|---------|-------|
| CSS Custom Properties | ✅ | IE not supported |
| Flexbox | ✅ | Full support |
| CSS Grid | ✅ | Full support |
| Backdrop Filter | ⚠️ | Safari requires `-webkit-` prefix |
| Intersection Observer | ✅ | Fallback included |
| Request Animation Frame | ✅ | Full support |
| Arrow Functions | ✅ | ES6 support required |
| Template Literals | ✅ | ES6 support required |
| Const/Let | ✅ | ES6 support required |

### Fallbacks

The code includes fallbacks for:
- **Reduced motion**: Respects `prefers-reduced-motion`
- **Older browsers**: Graceful degradation for unsupported features
- **No JavaScript**: Content remains accessible

---

## ⚡ Performance

### Performance Metrics

| Metric | Target | Achievement |
|--------|--------|-------------|
| First Contentful Paint | < 1.5s | ✅ |
| Time to Interactive | < 3s | ✅ |
| Total Bundle Size | ~50KB | ✅ |
| External Requests | 1 (fonts) | ✅ |
| JavaScript Size | ~8KB | ✅ |
| CSS Size | ~35KB | ✅ |

### Optimization Techniques

1. **Single File Architecture**
   - No additional HTTP requests
   - Faster initial load

2. **CSS Optimization**
   - Custom properties for efficient updates
   - No unused CSS frameworks

3. **JavaScript Optimization**
   - Event delegation where possible
   - Intersection Observer for efficient scroll detection
   - Request Animation Frame for smooth animations

4. **Lazy Loading**
   - Sections load only when needed
   - Reduced initial paint time

5. **Reduced Motion Support**
   - Respects user preferences
   - Better accessibility

---

## ♿ Accessibility

### WCAG 2.1 Compliance

| Criteria | Implementation |
|----------|----------------|
| **Semantic HTML** | Proper heading hierarchy (h1-h3) |
| **ARIA Labels** | Navigation, buttons, and links labeled |
| **Keyboard Navigation** | All interactive elements focusable |
| **Focus Indicators** | Visible focus styles on all elements |
| **Color Contrast** | Text meets WCAG AA contrast requirements |
| **Reduced Motion** | Respects `prefers-reduced-motion` |
| **Screen Reader** | Compatible with major screen readers |
| **Language** | `lang="id"` attribute set |

### ARIA Implementation

```html
<!-- Navigation -->
<nav class="nav" role="navigation" aria-label="Navigasi utama">
    <button class="nav-toggle" aria-label="Toggle menu" aria-expanded="false">
    <!-- ... -->
    </button>
</nav>

<!-- Social Links -->
<a href="..." class="social-link" aria-label="GitHub">
```

### Keyboard Navigation

- `Tab` - Navigate through interactive elements
- `Enter` - Activate links and buttons
- `Space` - Toggle mobile menu
- `Escape` - Close mobile menu

---

## 👨‍💻 Author

**Hizkia Letwar**

- 📍 Maluku Tengah, Indonesia
- 🎓 Student at SMK Negeri 1 Maluku Tengah
- 💼 OSIS IT Department Member
- 🎯 Focus: AI Engineering, Web Development
- 📧 Email: [manggadurian20@gmail.com](mailto:manggadurian20@gmail.com)

### Connect

[![GitHub](https://img.shields.io/badge/GitHub-%40Ikyletwar-181717?style=for-the-badge&logo=github)](https://github.com/Ikyletwar)
[![Instagram](https://img.shields.io/badge/Instagram-%40ikyletwar-E4405F?style=for-the-badge&logo=instagram)](https://www.instagram.com/ikyletwar/)
[![TikTok](https://img.shields.io/badge/TikTok-%40ikyletwar-000000?style=for-the-badge&logo=tiktok)](https://www.tiktok.com/@ikyletwar)

---

## 📄 License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).

```
MIT License

Copyright (c) 2026 Hizkia Letwar

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 🙏 Acknowledgments

- **Pak Bahy** — Teacher, programmer, and AI enthusiast who inspired the journey into vibe coding
- **Google Fonts** — For the beautiful Inter font family
- **Vibe Coding Community** — For pushing the boundaries of AI-assisted development

---

## 📝 Notes

### What is Vibe Coding?

**Vibe Coding** is an AI-assisted development approach where:
- Natural language prompts are used to generate code
- Focus is on creativity and problem-solving rather than syntax
- AI tools like Trae AI, ChatGPT, and Qwen are used as coding partners
- Rapid prototyping and iteration are possible

### Tools Used in Development

This website was built using:
- **Trae AI** — AI-powered code generation
- **Qwen Code CLI** — Command-line AI assistant
- **ChatGPT** — General purpose AI assistance
- **Gemini** — Google's AI assistant

---

<div align="center">

**Built with ❤️ and AI by Hizkia Letwar**

*"Elegance Is My Philosophy"*

</div>
