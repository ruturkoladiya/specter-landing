# Specter 👻

> An interactive, horror-themed landing page featuring a dynamic cursor spotlight reveal. 

This project is a premium, dark-themed web experience built to showcase advanced UI interactions. The signature feature is a custom-built canvas mask that creates a soft, glowing spotlight trailing the user's cursor, dynamically revealing a hidden, terrifying secondary layer beneath the dark, foggy graveyard exterior.

## 🎥 Interaction Demo

<div align="center">
  <!-- Place your recorded demo GIF or video here -->
  <img src="./public/demo.gif" alt="Hover Interaction Demo" width="800"/>
</div>

## ✨ Features

- **Interactive Cursor Reveal**: A smooth, interpolation-based `requestAnimationFrame` loop that paints a radial gradient mask to reveal hidden background elements.
- **Atmospheric Animations**: Custom CSS `@keyframes` that handle staggered, cinematic blur-reveals and slow Ken Burns zoom effects for a premium feel.
- **Fully Responsive**: Flawlessly adapts across mobile, tablet, and desktop viewports, with dynamic UI changes (like glassy navbar pills and hamburger menus).
- **Modern Typography**: Carefully selected pairings of `Inter` for crisp UI elements and `Playfair Display` (Italic) for dramatic, elegant headers.

## 🛠 Tech Stack

- **Framework**: React 18
- **Build Tool**: Vite
- **Styling**: Tailwind CSS (PostCSS/Autoprefixer)
- **Language**: TypeScript
- **Icons**: Lucide React

## 🚀 Getting Started

To get this project up and running on your local machine:

### 1. Install Dependencies
```bash
npm install
```

### 2. Start the Development Server
```bash
npm run dev
```

### 3. Build for Production
```bash
npm run build
```

## 📂 Project Structure
- `src/App.tsx` - Main entry point configuring the layout, typography, and animation classes.
- `src/components/RevealLayer.tsx` - The complex logic handling the hidden canvas and cursor-tracking mask overlay.
- `src/components/Navbar.tsx` - The responsive navigation bar component.
- `public/` - Contains the AI-generated high-resolution horror assets.
