# Project: Portfolio Website

## About
A personal portfolio site for a freelance designer/developer.
Target audience: potential clients and employers.

## Tech Stack
- Pure HTML, CSS, JavaScript (no frameworks)
- Use CSS custom properties for theming
- Vanilla JS for interactions and animations

## Design System
- Color palette:
  - Background: Deep navy (#0a0e1a)
  - Accent: Electric cyan (#00d4ff)
  - Secondary accent: Violet (#7c3aed)
  - Text primary: White (#ffffff)
  - Text secondary: #8892a4
  - Card bg: #111827
  - Border: #1f2937
- Fonts:
  - Headings: "Playfair Display" (Google Fonts)
  - Body: "Inter" (Google Fonts)
- Spacing scale: 8px base unit (8, 16, 24, 32, 48, 64, 96px)
- Border radius: 12px for cards, 6px for buttons, 50% for avatars
- Shadows: 0 4px 24px rgba(0, 212, 255, 0.08)
- Animations: 300ms ease transitions, subtle entry animations

## Pages Required
1. index.html — Hero, Services, Testimonials, CTA section
2. about.html — Story, Animated skills bars, Career timeline
3. work.html — Portfolio grid with filter tabs and hover overlays
4. contact.html — Contact form with floating labels, social links

## Shared Files
- styles.css — Global CSS variables, reset, typography, utilities
- nav.js — Sticky nav with scroll blur, mobile hamburger, active state
- footer.html — Shared footer snippet (or inline on each page)

## Rules
- NEVER use Bootstrap, Tailwind, or any CSS framework
- All images use https://picsum.photos/[width]/[height]?random=[n]
- Every page must be fully responsive (mobile-first, min breakpoint 320px)
- Accessibility: semantic HTML5, ARIA labels, visible focus states
- Performance: no external JS libraries, inline critical CSS
- Deploy target: Vercel static site (no build step needed)
- All internal links use relative paths (./about.html, not /about.html)
