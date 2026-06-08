# PulseGrid Experience

A multi-page cinematic SaaS website prototype built for VS Code, GitHub and Vercel.

## Stack

- React
- Vite
- TypeScript
- React Router
- Lucide React
- CSS-based immersive 3D look

## Pages

- Home
- Product
- Solutions
- Integrations
- Pricing
- Resources / Blog / Docs / FAQ / Changelog
- Security
- Customers / Case Studies
- Careers
- About
- Contact / Demo request
- Login
- Sign Up
- Demo Dashboard
- 404

## Run locally

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

## Preview production build

```bash
npm run preview
```

## Push to GitHub

```bash
git init
git add .
git commit -m "Initial PulseGrid website"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/pulsegrid-experience.git
git push -u origin main
```

## Deploy to Vercel

1. Create a GitHub repository and push this project.
2. Open Vercel.
3. Import the GitHub repository.
4. Framework preset: Vite.
5. Build command: `npm run build`.
6. Output directory: `dist`.
7. Deploy.

## Notes

This project intentionally avoids heavy external 3D models so it can run easily after download. The current 3D feeling is created with CSS scenes, animated panels, depth, gradients, and route-based immersive pages. Later, you can replace the CSS scene component with React Three Fiber / Three.js scenes.
