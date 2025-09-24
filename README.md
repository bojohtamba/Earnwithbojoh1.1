EarnWithBojoh - Version 1 Starter Package
=========================================

What's included:
- frontend/ : Simple React + Tailwind-like starter (no build step required; uses plain HTML/CSS/JS)
- backend/  : Minimal Node.js + Express server to handle newsletter signups and serve a simple API
- assets/   : Logo (SVG), favicon, sample affiliate config
- templates/: Email HTML templates (editable)
- docs/     : Deployment and admin instructions, Monetization strategy

How to run locally (quick test, no npm required for frontend):
1. Backend (Node.js required):
   - cd backend
   - npm install
   - npm start
   Backend runs on http://localhost:4000 by default.
2. Frontend:
   - Open frontend/index.html in a browser OR serve it via a static file server.
   - The frontend makes API calls to http://localhost:4000 for newsletter signup and click tracking.

Notes:
- This is a starter kit designed for quick deployment and later extension.
- For production, deploy frontend to Vercel/Netlify and backend to Render/Heroku/VPS. Enable HTTPS.
- See docs/deployment.md for more details.
