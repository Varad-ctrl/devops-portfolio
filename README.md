# Varad Jadhav — DevOps Portfolio

A modern, dark-themed, single-page portfolio built with plain HTML/CSS/JS (no build tools required).

## 📁 Structure

```
portfolio/
├── index.html          # Main page
├── style.css            # All styling (glassmorphism, animations, responsive)
├── script.js            # Particles, typed text, scroll reveals, form handler
├── README.md            # This file
└── assets/
    ├── profile.jpg       # ⚠️ ADD YOUR PHOTO HERE (see below)
    ├── resume.pdf         # ⚠️ ADD YOUR RESUME HERE (see below)
    ├── icons/             # (optional) extra icons you want to add
    └── screenshots/       # (optional) CI/CD or architecture screenshots
```

## ✅ Before you deploy — 2 required steps

1. **Add your photo**
   Save your professional photo as `assets/profile.jpg` (replace the placeholder).
   If no photo is present, the hero section automatically falls back to a "VJ" initials avatar — so the site won't break, but add the real photo for the best impression.

2. **Add your resume**
   Save your resume PDF as `assets/resume.pdf`. Both the navbar "Download CV" button and the Contact section "Download Resume" button already point to this path.

## ✏️ Easy edits

| What | Where |
|---|---|
| Email address | `index.html` — search for `varadjadhav@email.com` (appears twice) |
| GitHub link | Already set to `https://github.com/Varad-ctrl` |
| LinkedIn link | Already set to `https://www.linkedin.com/in/varad-jadhav-ba1355255` |
| Skill percentages | `index.html` — `.skill-bar-item` blocks in the Skills section |
| Certifications | `index.html` — `.cert-card` blocks in the Certifications section |
| Colors / theme | `style.css` — edit the `:root` CSS variables at the top |

## 🔌 Contact form (currently demo-only)

The form in the Contact section validates input and shows a success message, but **it is not wired to a real backend or email service yet**. To make it actually send you emails, pick one:

- **Formspree** (easiest, free tier): sign up, get a form endpoint, replace the `handleFormSubmit` function in `script.js` with a `fetch()` POST to your Formspree URL.
- **EmailJS**: similar approach, sends straight from the browser without a backend.
- **Your own API**: if you build a small backend, POST the form fields to it instead.

## 🚀 Deploy (free options, no build step needed)

- **GitHub Pages**: push this folder to a repo, enable Pages in repo settings, pointing to the root.
- **Netlify**: drag-and-drop this folder onto netlify.com/drop.
- **Vercel**: `vercel deploy` from inside this folder, or drag-and-drop via the dashboard.

## 🛠️ Tech used

Plain HTML5, CSS3 (custom properties, glassmorphism via `backdrop-filter`, CSS Grid/Flexbox), and vanilla JavaScript (Canvas-based particle background, IntersectionObserver for scroll reveals and counters, no frameworks, no dependencies).

---
Built for Varad Jadhav — DevOps Engineer, Sangli, Maharashtra.
