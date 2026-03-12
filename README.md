# Dark Fox — Official Website

> Parent company website for Dark Fox, a venture studio and design powerhouse.

---

## 🦊 About

This is the official website for **Dark Fox** — a venture studio, design agency, and creative lab. Built as a single-file HTML site with no frameworks or dependencies.

---

## 🚀 Live Site

(https://darkfox01.netlify.app/)

---

## 🗂 Project Structure

```
darkfox-website/
├── index.html       # Entire site — HTML, CSS, and JS in one file
└── README.md        # You are here
```

---

## ✨ Features

- Fully responsive — desktop, tablet, and mobile
- Mobile hamburger menu with slide-in drawer
- Smooth scroll animations and reveal effects
- Custom cursor (desktop only)
- Scrolling ticker
- Ventures showcase section
- Work / portfolio section with real projects
- Contact form powered by EmailJS (no backend needed)
- Single-file — no build tools, no dependencies

---

## 📬 Contact Form Setup (EmailJS)

The contact form uses [EmailJS](https://emailjs.com) to send emails without a backend.

To activate it, open `index.html` and find these 3 lines near the bottom:

```js
var EMAILJS_PUBLIC_KEY  = 'YOUR_PUBLIC_KEY';
var EMAILJS_SERVICE_ID  = 'YOUR_SERVICE_ID';
var EMAILJS_TEMPLATE_ID = 'YOUR_TEMPLATE_ID';
```

Replace with your real EmailJS credentials.

### Getting your keys

| Key | Where to find it |
|-----|-----------------|
| Public Key | EmailJS Dashboard → Account |
| Service ID | EmailJS Dashboard → Email Services |
| Template ID | EmailJS Dashboard → Email Templates |

### EmailJS Template Setup

**Subject:**
```
New Project Inquiry from {{from_name}} — Dark Fox
```

**Body:**
```
You have a new project inquiry from your Dark Fox website.

NAME:       {{from_name}}
EMAIL:      {{from_email}}
COMPANY:    {{company}}
SERVICE:    {{service}}

MESSAGE:
{{message}}

Reply directly to this email to respond to {{from_name}}.
— Dark Fox Contact Form
```

**Reply To field:** `{{reply_to}}`

---

## 🌍 Deployment

This site is deployed on **Netlify** via GitHub auto-deploy.

Every time you push to the `main` branch, Netlify automatically redeploys the site within 30 seconds.

### Manual update workflow

```bash
# 1. Edit index.html locally
# 2. Go to your GitHub repo
# 3. Upload the new index.html (it will replace the old one)
# 4. Netlify auto-deploys — live in ~30 seconds
```

---

## 🛠 Projects Featured

| Project | Type | URL |
|---------|------|-----|
| Slooze | SaaS Inventory Dashboard | [slooze-inventory-seven.vercel.app](https://slooze-inventory-seven.vercel.app/) |
| Travel Diary Holidays | Travel Agency | [resilient-biscochitos-f25db9.netlify.app](https://resilient-biscochitos-f25db9.netlify.app/) |
| Bizarre Collections | E-commerce Fashion | [sanjayas27.github.io/bizzare](https://sanjayas27.github.io/bizzare/) |

---

## 🏢 Ventures

| Venture | Status |
|---------|--------|
| Fox Studio | Active |
| Project 02 | Coming Soon |
| Project 03 | Coming Soon |

---

## 📄 License

© 2025 Dark Fox. All rights reserved.
