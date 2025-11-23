# Responsive Portfolio

A modern, fully responsive single-page portfolio website built with pure HTML and CSS. This project demonstrates responsive design principles, CSS Grid layouts, and modern CSS techniques.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Responsive Breakpoints](#responsive-breakpoints)
- [Key CSS Features](#key-css-features)
- [Learning Objectives](#learning-objectives)

## 🎯 Overview

This is a practice project focused on understanding responsive web design and CSS fundamentals. The portfolio showcases design services through an elegant, mobile-first layout that adapts seamlessly across all device sizes.

## ✨ Features

- **Fully Responsive Design** - Optimized for desktop, tablet, and mobile devices
- **Modern CSS Grid Layouts** - Complex grid systems for service showcase
- **CSS Custom Properties** - Maintainable theme system using CSS variables
- **Fluid Typography** - Responsive text sizing with `clamp()`
- **Semantic HTML5** - Clean, accessible markup structure
- **Mobile-First Approach** - Built with progressive enhancement

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern CSS features:
  - CSS Grid
  - Flexbox
  - CSS Custom Properties (Variables)
  - Media Queries
  - Fluid Typography with `clamp()`

## 📁 Project Structure

```
responsive-portfolio/
├── index.html          # Main HTML structure
├── style.css           # All styles and responsive rules
├── assets/             # Images, icons, and graphics
│   ├── logo.svg
│   ├── pattern-*.svg   # Service pattern images
│   ├── image-*.jpg     # Portfolio work images
│   └── favicon-32x32.png
└── README.md           # Project documentation
```

## 🚀 Getting Started

### Prerequisites

No build tools or dependencies required! Just a modern web browser.

### Installation

1. Clone or download this repository
2. Ensure all assets are present in the `assets/` folder
3. Open `index.html` in your web browser

### Required Assets

Make sure you have the following files in the `assets/` folder:

**Icons & Logo:**
- `logo.svg`
- `favicon-32x32.png`
- `icon-arrow-left.svg`
- `icon-arrow-right.svg`

**Pattern Images:**
- `pattern-graphic-design.svg`
- `pattern-ui-ux.svg`
- `pattern-apps.svg`
- `pattern-photography.svg`
- `pattern-illustrations.svg`
- `pattern-motion-graphics.svg`

**Content Images:**
- `image-amy.webp`
- `image-slide-1.jpg` through `image-slide-5.jpg`

## 📱 Responsive Breakpoints

The design adapts to three main screen sizes:

| Breakpoint | Screen Size | Layout Changes |
|------------|-------------|----------------|
| **Desktop** | > 768px | 6-column grid layout |
| **Tablet** | ≤ 768px | 4-column grid layout |
| **Mobile** | ≤ 380px | 2-column grid layout, stacked content |

## 🎨 Key CSS Features

### CSS Custom Properties

The project uses CSS variables for easy theming:

```css
:root {
  --clr-neutral-900: #030303;
  --clr-summer-yellow-500: #f6a560;
  --font-family-Jakarta: "Plus Jakarta Sans", sans-serif;
  --radius-full: 999px;
}
```

### CSS Grid Layout

Complex grid system for services section:

```css
grid-template-areas:
  "graphic graphic ui-ux apps photography photography"
  "graphic graphic illus illus motion motion";
```

### Fluid Typography

Responsive text sizing:

```css
--font-size-h1: clamp(1.5rem, 1.9898rem + 2.1769vw, 2.5rem);
```

### Media Queries

Responsive adjustments at multiple breakpoints:

- Mobile: `@media screen and (max-width: 380px)`
- Tablet: `@media screen and (max-width: 768px)`

## 📚 Learning Objectives

This project was created to practice and understand:

1. **Responsive Design Fundamentals**
   - Mobile-first development approach
   - Breakpoint strategy
   - Flexible layouts

2. **CSS Layout Techniques**
   - CSS Grid for complex layouts
   - Flexbox for component alignment
   - Positioning strategies

3. **Modern CSS Practices**
   - CSS Custom Properties
   - Fluid typography
   - Efficient selector usage

4. **Best Practices**
   - Semantic HTML structure
   - Maintainable CSS organization
   - Performance optimization

## 🌐 Browser Support

This project works best in modern browsers that support:
- CSS Grid
- CSS Custom Properties
- Flexbox
- Media Queries

Recommended browsers:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📝 Notes

This is an educational project created to understand responsive design principles and CSS layout techniques. The project focuses on pure CSS solutions without JavaScript dependencies.

---


