# Harish Pal — Premium Web Developer Portfolio

A world-class, premium portfolio website designed for creative web developer **Harish Pal**. This website is styled using Apple-inspired liquid-glass design patterns and is optimized for high conversion rates.

Live preview integration is set up via GitHub and Cloudflare Pages.

---

## 🚀 Tech Stack

- **Framework**: [Next.js](https://nextjs.org/) (App Router)
- **UI Library**: [React 19](https://react.dev/) & [TypeScript](https://www.typescriptlang.org/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) (translucent overlays, glassmorphism filters, keyframes)
- **Animations**: [Framer Motion](https://www.framer.com/motion/) (smooth transitions, magnetic buttons, count-up counters, and slide marquees)
- **Icons**: [Lucide React](https://lucide.dev/)

---

## ✨ Features

1. **Apple Liquid-Glass Theme**: High-fidelity translucent styling (`backdrop-filter: blur(28px)`) with glowing highlights and sweeping light shine reflections on hover.
2. **Global Floating Navbar**: Modern SaaS-style header that floats seamlessly at the top of the viewport with responsive navigation links and a glowing CTA button.
3. **Hero Live Project Preview**: A floating mockup browser player on the right side of the hero section that embeds a live, scrollable interactive iframe of the latest project.
4. **Horizontal Scroll Portfolio**: Responsive, horizontal-scrolling project track with scroll-snapping, glassy hover reflections, and a custom scrollbar indicator.
5. **Horizontal Testimonials Marquee**: Clean grid marquee that automatically glides client testimonials left-to-right under the top sections.
6. **Glassy FAQ Accordion & Forms**: Premium interactive accordion and contact form with success animations.

---

## 🛠️ Getting Started

Follow these steps to run the website locally on your computer:

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) installed (version 18.x or later recommended).

### 1. Clone the Project
```bash
git clone https://github.com/harishpalji217/portfolio-website.git
cd portfolio-website
```

### 2. Install Dependencies
```bash
npm install
```

### 3. Run the Development Server
```bash
npm run dev
```
Open **[http://localhost:3000](http://localhost:3000)** in your browser to view the live local preview.

### 4. Create a Production Build
Compile and bundle the website for production:
```bash
npm run build
```

### 5. Start the Production Server
```bash
npm run start
```

---

## 🌐 Deployment

The repository is pre-configured for instant serverless deployments:
- **Cloudflare Pages / Vercel**: Connect this repository to your hosting provider. The build settings are:
  - **Build Command**: `npm run build`
  - **Output Directory**: `.next` or default output directory
