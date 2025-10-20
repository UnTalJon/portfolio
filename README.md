![Project Banner](./public/assets/images/project-banner.gif)

# Portfolio

A modern, responsive portfolio website built with Astro, featuring smooth animations and an elegant design.

## ✨ Features

- **Modern Design**: Clean and professional layout with smooth animations
- **Responsive**: Optimized for all device sizes
- **Fast Performance**: Built with Astro for optimal loading speeds
- **Smooth Animations**: Enhanced user experience with GSAP and Lenis
- **TypeScript**: Type-safe development environment

## 🛠️ Tech Stack

- **Framework**: [Astro](https://astro.build)
- **Animations**: [GSAP](https://greensock.com/gsap/)
- **Smooth Scrolling**: [Lenis](https://lenis.studiofreight.com/)
- **Icons**: [Lucide](https://lucide.dev/)
- **Font**: [Sometype Mono](https://www.fontshare.com/fonts/sometype-mono)
- **Runtime**: [Bun](https://bun.sh/)

## 🚀 Getting Started

### Prerequisites

Make sure you have [Bun](https://bun.sh/) installed on your machine.

### Installation

1. Clone the repository:
```bash
git clone https://github.com/UnTalJon/portfolio.git
cd portfolio
```

2. Install dependencies:
```bash
bun install
```

3. Start the development server:
```bash
bun dev
```

The site will be available at `http://localhost:4321`

## 📝 Commands

| Command | Action |
|---------|--------|
| `bun install` | Install dependencies |
| `bun dev` | Start development server at `localhost:4321` |
| `bun build` | Build production site to `./dist/` |
| `bun preview` | Preview production build locally |
| `bun astro ...` | Run Astro CLI commands |


## 🚀 Deployment

The project includes Docker configuration for easy deployment:

```bash
docker build -t portfolio .
docker run -p 3000:3000 portfolio
```
