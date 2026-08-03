# AshvaLekh — Portfolio

A cinematic, scroll-driven developer portfolio built with React, Tailwind CSS, and GSAP — featuring a frame-by-frame scroll animation hero, animated sections, and a working contact form.

![Status](https://img.shields.io/badge/status-active-success)
![React](https://img.shields.io/badge/React-19-blue)
![Vite](https://img.shields.io/badge/Vite-8-purple)

## 🚀 Live Demo
[View Live Site](#) <!-- add your deployed URL here -->

## ✨ Features

- **Cinematic Hero** — scroll-scrubbed image sequence animation powered by GSAP ScrollTrigger
- **About** — bio, tech stack, and education overview
- **Services** — core offerings with an experience highlight sidebar
- **Selected Works** — project showcase with tags and live/GitHub links
- **Contact** — animated contact section with a working EmailJS-powered form
- Fully responsive, dark-themed UI with subtle HUD-style accents

## 🛠️ Tech Stack

- **Framework:** React 19 + Vite
- **Styling:** Tailwind CSS
- **Animation:** GSAP (ScrollTrigger) + Framer Motion
- **Icons:** React Icons
- **Forms:** EmailJS
- **Notifications:** React Toastify

## 📦 Getting Started

### Prerequisites
- Node.js (v18 or higher)
- npm

### Installation

```bash
git clone https://github.com/your-username/ashvalekh-portfolio.git
cd ashvalekh-portfolio
npm install
```

### Development

```bash
npm run dev
```

Visit `http://localhost:5173` to view it locally.

### Build for Production

```bash
npm run build
npm run preview
```

## ⚙️ Configuration

Before deploying, update the following:

1. **Contact form** — add your own [EmailJS](https://www.emailjs.com/) Service ID, Template ID, and Public Key in `src/components/Contact.jsx`
2. **Social links** — update GitHub/LinkedIn/Twitter/Instagram URLs in `src/components/Hero.jsx` and `src/components/Footer.jsx`
3. **Project images** — add screenshots to `public/projects/` (see filenames in `src/components/Portfolio.jsx`)
4. **Hero/Contact animation frames** — replace image sequences in `src/assets/images/` and `public/image3/`
5. **Resume** — add your `resume.pdf` to the `public/` folder

## 📄 License

This project is open source and available for personal use.

## 📬 Contact

**Ashutosh Singh Rathore**
Email: ashutoshsinghr92@gmail.com
[LinkedIn](#) · [GitHub](#)
