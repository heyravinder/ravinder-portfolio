# Ravinder Singh – Portfolio

A glassy, playful developer portfolio built with React and Vite.

## Features
Typing animation, dark/light mode, custom cursor, smooth scrolling, 3D tilt project cards, particle background, animated navigation, skill bars and a gravity-ball playground, page transitions, back-to-top, command palette (Ctrl/⌘ + K), dev notes, workflow, availability and a validated contact form with spam protection.

## Run it
```bash
npm install
npm run dev      # http://localhost:5173
npm run build    # production build in dist/
```

## Edit your content
Everything you will want to change lives in `src/data.jsx`: links, email, projects, skill levels, currently-learning list, services, workflow and dev notes.

## Make the contact form send real messages
1. Create a free form at [Formspree](https://formspree.io) or [Web3Forms](https://web3forms.com).
2. Paste its URL into `FORM_ENDPOINT` in `src/data.jsx`.

Without an endpoint, the form validates the fields and opens the visitor's email app with the message filled in. A hidden honeypot field and a timing check block basic bots.

## Deploy on Vercel
1. Push this folder to a GitHub repository.
2. On [vercel.com](https://vercel.com), click **Add New → Project** and import the repo.
3. Vercel detects Vite automatically. Click **Deploy**.
