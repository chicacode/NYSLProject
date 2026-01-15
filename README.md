# MDHL - Mighty Ducks Hockey League Website

![MDHL Banner](https://img.shields.io/badge/MDHL-Hockey%20League-1e3a8a?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![Accessibility](https://img.shields.io/badge/WCAG%202.1-AA%20Compliant-green?style=for-the-badge)

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Accessibility Features](#accessibility-features)
- [Browser Support](#browser-support)
- [Customization Guide](#customization-guide)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🎯 Overview

The **Mighty Ducks Hockey League (MDHL)** website is a modern, accessible, single-page application redesigned from a 2018 multi-page static website. This project demonstrates best practices in web development, focusing on:

- **Accessibility**: WCAG 2.1 AA compliance
- **Responsive Design**: Mobile-first approach
- **User Experience**: Smooth navigation and intuitive interface
- **Performance**: Fast loading times with pure HTML/CSS
- **Maintainability**: Clean, semantic code structure

### Live Demo

🔗 [View Live Website](https://chicacode.github.io/NYSLProject/)

### Original Website

The original 2018 version can be found [here](https://chicacode.github.io/NYSLProject/index.html)

## ✨ Features

### 🏠 Home Section
- Eye-catching hero section with call-to-action buttons
- Gradient background with modern design
- Clear value proposition

### ℹ️ About Section
- League history and mission statement
- Two-column layout with mission highlight box
- Engaging content presentation

### 📜 Rules Section
- Six comprehensive rule cards
- Numbered indicators for easy reference
- Hover effects for better interactivity
- Covers eligibility, equipment, conduct, attendance, fair play, and game day rules

### 🏒 Games Schedule
- Responsive data table
- Sortable game information (Date, Time, Teams, Location, Division)
- Mobile-optimized horizontal scrolling
- Clean, readable design

### 📝 Registration Form
- Comprehensive player registration
- Form validation with required field indicators
- Accessible form controls with proper labels
- Fields include:
  - Personal information (name, DOB, gender)
  - Contact details (email, phone, address)
  - Hockey experience level
  - Parent/guardian information
  - Emergency contacts
  - Medical information
  - Consent checkboxes

### 📞 Contact Section
- Contact information display
- Quick contact form
- Office hours and location details
- Email and phone links

### 🧭 Navigation
- Fixed header with smooth scroll
- Mobile-responsive hamburger menu
- Active section highlighting
- Skip-to-content link for accessibility

## 🛠 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with custom properties
- **Vanilla JavaScript**: Interactive features (no frameworks)
- **Responsive Design**: Mobile-first approach
- **Flexbox & Grid**: Modern layout techniques

### No Dependencies!

This project uses **zero external libraries or frameworks**, making it:
- ⚡ Lightning fast
- 📦 Lightweight (< 50KB total)
- 🔒 Secure (no third-party vulnerabilities)
- 🔧 Easy to maintain

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A text editor (VS Code, Sublime Text, Atom, etc.)
- Basic knowledge of HTML/CSS (for customization)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://chicacode.github.io/NYSLProject/
   cd mdhl-website
   ```

2. **Open the project**
   - Simply open `index.html` in your web browser

   **Using VS Code Live Server:**
   - Install the "Live Server" extension
   - Right-click on `index.html`
   - Select "Open with Live Server"

3. **View in browser**
   - Navigate to `http://localhost` (or the port your server uses)

## 📁 Project Structure

```
NYSLPROJECT/
│
├── index.html              # Main HTML file (single-page app)
├── README.md              # This file
├── LICENSE                # License information
│
└── assets/                # Optional folder for additional assets
    ├── images/            # Images (if separated from HTML)
    ├── icons/             # Icon files
    └── documents/         # Downloadable PDFs, waivers, etc.
└── javascript/
    |-- script.js          # Main Javascript
└──styles
    └──styles.css          # Main CSS
```

### Code Organization

The `index.html` file contains:
- **HTML Structure**: Semantic markup with proper ARIA labels
- **CSS Styles**: Embedded in `<style>` tag in the `<head>`
- **JavaScript**: Embedded in `<script>` tag at the end of `<body>`

## ♿ Accessibility Features

This website follows **WCAG 2.1 Level AA** guidelines:

### Keyboard Navigation
- ✅ All interactive elements are keyboard accessible
- ✅ Visible focus indicators on all focusable elements
- ✅ Skip-to-content link for screen readers
- ✅ Logical tab order throughout the page

### Screen Reader Support
- ✅ Semantic HTML5 elements (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`)
- ✅ ARIA labels and landmarks
- ✅ Descriptive link text
- ✅ Form labels properly associated with inputs
- ✅ Required field indicators (`aria-required="true"`)

### Visual Accessibility
- ✅ Color contrast ratio meets WCAG AA standards (4.5:1 for normal text)
- ✅ Text is resizable up to 200% without breaking layout
- ✅ Focus indicators have 3:1 contrast ratio
- ✅ No content relies solely on color to convey meaning

### Form Accessibility
- ✅ Clear error messages
- ✅ Required field indicators (visual and semantic)
- ✅ Proper input types for better mobile experience
- ✅ Helpful placeholder text
- ✅ Logical grouping of form fields

### Testing Tools Used
- [WAVE Browser Extension](https://wave.webaim.org/extension/)
- [axe DevTools](https://www.deque.com/axe/devtools/)
- Keyboard-only navigation testing
- Screen reader testing (NVDA, JAWS, VoiceOver)

## 🌐 Browser Support

| Browser | Version | Status |
|---------|---------|--------|
| Chrome | 90+ | ✅ Fully Supported |
| Firefox | 88+ | ✅ Fully Supported |
| Safari | 14+ | ✅ Fully Supported |
| Edge | 90+ | ✅ Fully Supported |
| Opera | 76+ | ✅ Fully Supported |

### Mobile Support
- ✅ iOS Safari 14+
- ✅ Chrome Mobile
- ✅ Firefox Mobile
- ✅ Samsung Internet

## 🎨 Customization Guide

### Changing Colors

Colors are defined as CSS custom properties in the `:root` selector:

```css
:root {
    --primary-blue: #1e3a8a;      /* Main brand color */
    --secondary-blue: #3b82f6;    /* Secondary brand color */
    --accent-orange: #f97316;     /* Accent/CTA color */
    --light-bg: #f8fafc;          /* Light background */
    --white: #ffffff;             /* White */
    --text-dark: #1e293b;         /* Dark text */
    --text-gray: #64748b;         /* Gray text */
    --border-color: #e2e8f0;      /* Border color */
}
```

### Changing Typography

Update the `body` font-family:

```css
body {
    font-family: 'Your-Font', -apple-system, BlinkMacSystemFont, sans-serif;
}
```

### Modifying Layout

- **Max width**: Change `max-width: 1400px` in sections
- **Padding**: Adjust `padding: 5rem 2rem` in sections
- **Grid columns**: Modify `grid-template-columns` properties

### Adding New Sections

1. Add new `<section id="new-section">` in HTML
2. Add navigation link: `<li><a href="#new-section">New Section</a></li>`
3. Style your section in the CSS

## 🌍 Deployment

### GitHub Pages

1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. **Enable GitHub Pages**
   - Go to repository Settings
   - Navigate to "Pages" section
   - Select branch: `main`
   - Select folder: `/ (root)`
   - Click "Save"

3. **Access your site**
   - Your site will be available at: `https://yourusername.github.io/repository-name/`




3. **Follow prompts** and your site will be live!

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

### Reporting Bugs

1. Check if the bug has already been reported
2. Create a new issue with:
   - Clear title and description
   - Steps to reproduce
   - Expected vs actual behavior
   - Screenshots (if applicable)
   - Browser and OS information

### Suggesting Enhancements

1. Create an issue describing your enhancement
2. Explain why this feature would be useful
3. Provide examples or mockups if possible

### Pull Requests

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m 'Add some AmazingFeature'`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Code Style Guidelines

- Use semantic HTML5 elements
- Follow BEM naming convention for CSS classes (if adding new ones)
- Write accessible code (WCAG 2.1 AA)
- Comment complex CSS/JavaScript
- Test on multiple browsers and devices



## 📞 Contact

**Project Maintainer**: Geri <3

- 🌐 Website: [yourwebsite.com](https://chicacode.dev)
- 💼 LinkedIn: [Your LinkedIn](https://linkedin.com/in/geraldinehalattrach)
- 🐙 GitHub: [@yourusername](https://github.com/chicacode)

**MDHL League Office**:
- 📍 Address: 1234 Hockey Lane, Chicago, IL 60601
- 📞 Phone: (312) 555-1234
- 📧 Email: info@mdhl.com

## 🙏 Acknowledgments

- Original 2018 website design inspiration
- [WCAG Guidelines](https://www.w3.org/WAI/WCAG21/quickref/) for accessibility standards
- Modern CSS techniques from [CSS-Tricks](https://css-tricks.com/)
- Icon inspiration from various open-source projects

## 📊 Project Stats

![GitHub repo size](https://img.shields.io/github/repo-size/chicacode/NYSLPROJECT)
![GitHub last commit](https://img.shields.io/github/last-commit/chicacode/NYSLPROJECT)
![GitHub issues](https://img.shields.io/github/issues/chicacode/NYSLPROJECT)
![GitHub pull requests](https://img.shields.io/github/issues-pr/chicacode/NYSLPROJECT)

## 🗺️ Roadmap

Future enhancements planned:

- [ ] Add player profiles section
- [ ] Integrate live score updates
- [ ] Add photo gallery
- [ ] Implement dark mode toggle
- [ ] Add multilingual support (Spanish, French)
- [ ] Create team roster management system
- [ ] Add parent testimonials section
- [ ] Integrate payment processing for registration
- [ ] Add blog/news section
- [ ] Create mobile app
- [ ] Migrte to React 19

---

**⭐ If you found this project helpful, please consider giving it a star!**

Made with ❤️ by Geri and Claude.

Last Updated: January 2026