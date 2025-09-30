# 🎮 RPG Game - Modern Gaming Website

A stunning, modern website showcasing an RPG game with smooth animations and interactive elements. Built with React, GSAP, and Tailwind CSS.

[![Netlify Status](https://api.netlify.com/api/v1/badges/7ba412ca-2f5e-439d-a56f-d2c5994686ab/deploy-status)](https://app.netlify.com/projects/games-rpg/deploys)

## 🌟 Live Demo

Visit the live website: [https://games-rpg.netlify.app/](https://games-rpg.netlify.app/)

## ✨ Features

- **Smooth Animations** - Advanced GSAP animations for an immersive experience
- **Responsive Design** - Fully responsive across all devices
- **Modern UI/UX** - Contemporary design with glassmorphism and gradient effects
- **Interactive Elements** - Engaging hover effects and scroll-triggered animations
- **Custom Typography** - Multiple custom fonts for unique branding
- **Optimized Performance** - Fast loading times with Vite

## 🛠️ Tech Stack

- **Framework:** React 19.1.1
- **Build Tool:** Vite 7.1.7
- **Styling:** Tailwind CSS 3.4.17
- **Animations:** GSAP 3.13.0 with @gsap/react
- **Icons:** React Icons 5.5.0
- **Hooks:** react-use 17.6.0
- **Deployment:** Netlify

## 📋 Prerequisites

Before you begin, ensure you have installed:
- Node.js (v18 or higher)
- npm or yarn

## 🚀 Getting Started

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/rpg-game-website.git
cd rpg-game-website
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm run dev
```

4. Open your browser and visit `http://localhost:5173`

## 📜 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## 📁 Project Structure

```
rpg-game-website/
├── public/
│   └── fonts/           # Custom font files
├── src/
│   ├── components/
│   │   ├── Navbar.jsx   # Navigation component
│   │   ├── Hero.jsx     # Hero section
│   │   ├── About.jsx    # About section
│   │   ├── Features.jsx # Features showcase
│   │   ├── Story.jsx    # Story section
│   │   ├── Contact.jsx  # Contact form
│   │   └── Footer.jsx   # Footer component
│   ├── App.jsx          # Main application component
│   ├── main.jsx         # Entry point
│   └── index.css        # Global styles and Tailwind directives
├── index.html
├── package.json
├── tailwind.config.js
├── vite.config.js
└── README.md
```

## 🎨 Custom Fonts

This project uses several custom fonts:
- **Zentry** - Primary display font
- **General Sans** - Body text
- **Circular Web** - Supplementary text
- **Robert** (Medium & Regular) - Additional typography

Make sure to include font files in the `/public/fonts/` directory.

## 🎭 Sections Overview

### Hero
Eye-catching hero section with animated elements and call-to-action

### About
Detailed information about the RPG game with scroll animations

### Features
Showcases key features with interactive Bento grid layout

### Story
Immersive storytelling section with image masks and 3D transforms

### Contact
Contact form with custom clip-path designs

### Footer
Site information and social links

## 🌈 Color Palette

```css
Blue Shades:
- #DFDFF0 (50)
- #DFDFF2 (75)
- #F0F2FA (100)
- #4FB7DD (300)

Violet:
- #5724FF (300)

Yellow:
- #8E983F (100)
- #EDFF66 (300)
```

## 📦 Building for Production

```bash
npm run build
```

This will generate optimized files in the `dist/` directory.

## 🚢 Deployment

The site is automatically deployed to Netlify on every push to the main branch.

### Manual Deployment

1. Build the project
```bash
npm run build
```

2. Deploy the `dist` folder to your hosting service

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 👏 Acknowledgments

- Design inspiration from Awwwards-winning websites
- GSAP for powerful animation capabilities
- Tailwind CSS for rapid UI development
- React community for excellent tools and libraries

## 📧 Contact

Project Link: [https://games-rpg.netlify.app/](https://games-rpg.netlify.app/)

---

Made with 💚 and React
