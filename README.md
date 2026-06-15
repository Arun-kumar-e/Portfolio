# Portfolio

A modern, high-performance developer portfolio built with **Astro** and **Tailwind CSS v4**. Features a glassmorphism design, smooth animations, and a cohesive dark palette with purple-to-cyan gradient accents.

Inspired by the layout structure of Brittany Chiang's portfolio.

---

## Features

- **Responsive Design**: Optimized for mobile, tablet, and desktop viewports
- **Glassmorphic Navigation**: Sticky header with backdrop-blur and interactive hover highlights
- **Terminal Mockup**: Interactive CLI-style showcase component
- **Comprehensive Sections**:
  - About: Profile introduction and background
  - Skills: Grid cards showcasing technical expertise
  - Experience: Professional work history timeline
  - Projects: Glassmorphic cards with technology tags and links
  - Education: Academic credentials
  - Contact: Built-in copy-to-clipboard email utility with animated feedback
- **Micro-Animations**: Hover scales, neon glow borders, gradient shifts, and smooth scrolls

---

## Tech Stack

| Category | Technology |
|----------|------------|
| Framework | [Astro v6](https://astro.build/) |
| Styling | [Tailwind CSS v4](https://tailwindcss.com/) |
| Language | [TypeScript](https://www.typescript.org/) |
| Deployment | [Vercel](https://vercel.com) |

---

## Project Structure

```text
/
├── public/               # Static assets
├── src/
│   ├── assets/           # Media assets
│   ├── components/       # Reusable Astro components
│   │   ├── Card.astro
│   │   ├── Navbar.astro
│   │   └── TerminalMockup.astro
│   ├── layouts/          # Page layouts
│   │   └── Layout.astro
│   ├── pages/            # Page routing
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── package.json
├── tsconfig.json
└── astro.config.mjs
```

---

## Getting Started

### Prerequisites

- Node.js >= 22.12.0

### Installation

```bash
npm install
```

### Development

```bash
npm run dev
```

The application starts at `http://localhost:4321`.

### Build

```bash
npm run build
```

### Preview

```bash
npm run preview
```

---

## Deployment

### Vercel

1. Import the repository into your [Vercel Dashboard](https://vercel.com/dashboard)
2. Vercel auto-detects Astro with these settings:
   - **Framework Preset**: Astro
   - **Build Command**: `npm run build`
   - **Output Directory**: `dist`
3. Click **Deploy**

---

## License

MIT
