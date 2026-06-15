# 🌌 Purple-Cyan Dark Theme Portfolio

A modern, high-performance developer portfolio built with the **Astro** web framework and **Tailwind CSS v4**. It features a stunning glassmorphism design, smooth interactive animations, and a cohesive dark palette highlighted by purple-to-cyan gradient accents.

Inspired by the layout structure of Brittany Chiang's portfolio.

---

## 🚀 Key Features

- **Responsive Design**: Optimized for mobile, tablet, and desktop viewports.
- **Glassmorphic Navigation**: Sticky header with backdrop-blur navigation links and interactive hover highlights.
- **Terminal Mockup**: An interactive CLI-style showcase component displaying developer commands and status.
- **Comprehensive Sections**:
  - 👤 **About**: Profile introduction, bio, and background.
  - ⚡ **Skills**: Grid cards showcasing categorized technical expertise.
  - 💼 **Experience**: Chronological timeline of professional work history.
  - 💻 **Projects**: Glassmorphic project cards featuring technologies, github links, and live previews.
  - 🎓 **Education**: Academic credentials.
  - 📧 **Contact**: Seamless interaction with a built-in copy-to-clipboard email copy utility and animated feedback toast.
- **Micro-Animations**: Hover scales, neon glow borders, gradient shifts, and smooth scrolls.

---

## 🛠️ Technology Stack

- **Framework**: [Astro v6](https://astro.build/) (Static Site Generation for lightning-fast speeds)
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/) & PostCSS
- **Language**: [TypeScript](https://www.typescript.org/)
- **Target Deployment**: Vercel

---

## 📂 Project Structure

```text
/
├── .agents/              # Agent local skills & metadata (Excluded from Git/Vercel)
├── public/               # Static assets (Favicons, images)
├── src/
│   ├── assets/           # Media assets
│   ├── components/       # Reusable Astro components
│   │   ├── Card.astro           # Generic container cards
│   │   ├── Navbar.astro         # Header navigation
│   │   └── TerminalMockup.astro # Animated terminal layout
│   ├── layouts/          # Page layouts
│   │   └── Layout.astro         # Main shell with metadata, fonts, global styles
│   ├── pages/            # Page routing
│   │   └── index.astro          # Single-page portfolio entry
│   └── styles/
│       └── global.css    # Global Tailwind v4 directives and CSS animations
├── package.json          # Node dependencies & project scripts
├── tsconfig.json         # TypeScript configuration
└── astro.config.mjs      # Astro configuration
```

---

## ⚡ Getting Started

### Prerequisites

Ensure you have **Node.js >= 22.12.0** installed.

### Installation

Install all required dependencies:

```bash
npm install
```

### Development Server

Run the development server locally:

```bash
npm run dev
```

The application will start at `http://localhost:4321`.

### Production Build

Compile the static production site into the `dist/` directory:

```bash
npm run build
```

Preview your local production build:

```bash
npm run preview
```

---

## ☁️ Deployment

### Deploying to Vercel

This project is fully configured for deployment on [Vercel](https://vercel.com).

1. Import the repository into your Vercel Dashboard.
2. Vercel automatically detects **Astro** and configures the following settings:
   - **Framework Preset**: `Astro`
   - **Build Command**: `npm run build` or `astro build`
   - **Output Directory**: `dist`
3. Click **Deploy**.

> [!NOTE]
> All local configurations, local environments (`.env*.local`), vscode configurations (`.vscode/`), and agent-specific files (`.agents/`, `AGENTS.md`, `GEMINI.md`, `skills-lock.json`) are automatically excluded from the Git repository and Vercel deployments via `.gitignore`.
