---
version: beta
name: Purple-Cyan Dark Theme Portfolio
description: A dark-themed portfolio inspired by brittanychiang.com layout with purple-cyan gradient accents. Features glassmorphism cards, smooth animations, and a modern developer aesthetic.

colors:
  primary: "#8b5cf6"
  primary-deep: "#6d28d9"
  secondary: "#06b6d4"
  secondary-deep: "#0891b2"
  background: "#0a0a0f"
  surface: "#111827"
  surface-light: "#1f2937"
  surface-hover: "#374151"
  text: "#f9fafb"
  text-secondary: "#d1d5db"
  text-muted: "#6b7280"
  border: "#1f2937"
  border-light: "#374151"
  gradient-purple: "#8b5cf6"
  gradient-cyan: "#06b6d4"
  gradient-start: "#8b5cf6"
  gradient-end: "#06b6d4"
  success: "#10b981"
  error: "#ef4444"
  warning: "#f59e0b"

typography:
  display-xl:
    fontFamily: Inter, system-ui, -apple-system, sans-serif
    fontSize: 48px
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: -0.02em
  display-lg:
    fontFamily: Inter, system-ui, -apple-system, sans-serif
    fontSize: 36px
    fontWeight: 700
    lineHeight: 1.2
    letterSpacing: -0.02em
  display-md:
    fontFamily: Inter, system-ui, -apple-system, sans-serif
    fontSize: 24px
    fontWeight: 600
    lineHeight: 1.3
    letterSpacing: -0.01em
  body-lg:
    fontFamily: Inter, system-ui, -apple-system, sans-serif
    fontSize: 18px
    fontWeight: 400
    lineHeight: 1.6
  body-md:
    fontFamily: Inter, system-ui, -apple-system, sans-serif
    fontSize: 16px
    fontWeight: 400
    lineHeight: 1.6
  body-sm:
    fontFamily: Inter, system-ui, -apple-system, sans-serif
    fontSize: 14px
    fontWeight: 400
    lineHeight: 1.5
  caption:
    fontFamily: "JetBrains Mono", ui-monospace, monospace
    fontSize: 12px
    fontWeight: 500
    lineHeight: 1.4
    letterSpacing: 0.05em

spacing:
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  2xl: 48px
  3xl: 64px
  4xl: 96px

rounded:
  sm: 6px
  md: 8px
  lg: 12px
  xl: 16px
  full: 9999px

components:
  glass-card:
    backgroundColor: "rgba(17, 24, 39, 0.6)"
    borderColor: "rgba(139, 92, 246, 0.1)"
    backdropFilter: "blur(12px)"
    rounded: "{rounded.lg}"
    padding: "{spacing.lg}"
  
  gradient-button:
    background: "linear-gradient(135deg, {colors.gradient-purple}, {colors.gradient-cyan})"
    textColor: "#ffffff"
    rounded: "{rounded.full}"
    padding: "{spacing.sm} {spacing.lg}"
  
  nav-link:
    textColor: "{colors.text-secondary}"
    hoverColor: "{colors.text}"
    typography: "{typography.body-sm}"
---

## Overview

This portfolio uses a deep dark theme with purple-cyan gradient accents, inspired by modern developer portfolios like brittanychiang.com. The design features glassmorphism effects, subtle gradients, and smooth animations to create an immersive, professional experience.

## Design Principles

1. **Dark First**: Deep dark backgrounds (#0a0a0f) with layered surfaces for depth
2. **Gradient Accents**: Purple-to-cyan gradients for CTAs, highlights, and decorative elements
3. **Glassmorphism**: Translucent cards with backdrop blur and subtle borders
4. **Minimal Motion**: Subtle hover effects and smooth transitions
5. **Clear Hierarchy**: Strong typography with Inter font family

## Layout Structure (brittanychiang.com inspired)

- **Header**: Sticky nav with logo, navigation links, and CTA
- **Hero**: Large name, title, tagline with gradient text effects
- **About**: Bio section with avatar and quick facts
- **Skills**: Card grid showcasing technical abilities
- **Experience**: Timeline-style work history
- **Projects**: Feature cards with terminal mockups
- **Education**: Credential cards
- **Contact**: CTA section with email and social links
- **Footer**: Minimal footer with links

## Color Application

- **Background**: #0a0a0f (main), #111827 (surface), #1f2937 (elevated)
- **Text**: #f9fafb (primary), #d1d5db (secondary), #6b7280 (muted)
- **Accents**: Purple (#8b5cf6) and Cyan (#06b6d4) gradients
- **Borders**: Subtle purple/cyan tints on dark surfaces

## Typography

- **Headings**: Inter 700 weight, tight letter-spacing
- **Body**: Inter 400 weight, comfortable line-height
- **Code/Labels**: JetBrains Mono for technical elements

## Animations

- Smooth scroll navigation
- Card hover glow effects (purple/cyan tint)
- Button hover scale transforms
- Subtle gradient shifts on focus
