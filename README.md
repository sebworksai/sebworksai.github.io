# SEBWORKS — AI Automation Consulting

> **Live site:** [sebworks.github.io](https://sebworks.github.io)

Personal website for **Sebenzile Gabone**, AI Automation Consultant based in Pretoria, South Africa.

---

## About This Site

This is a single-page website built with HTML, CSS, and vanilla JavaScript. It is hosted on GitHub Pages and requires no framework, build tool, or server to run.

The site is designed to:
- Introduce SEBWORKS and the services offered
- Guide small business owners through the problem of time-draining admin
- Convert visitors into discovery call bookings via a Formspree-connected contact form
- Provide a direct WhatsApp contact option

---

## Pages & Sections

| Section | Description |
|---|---|
| **Hero** | Headline, key stats, and primary CTA |
| **Guide Band** | Sets the tone — invites visitors to scroll as a conversation |
| **About** | Sebenzile's story, engineering background, and approach |
| **The Problem** | Journey-style timeline of the 3 pain points and transformation |
| **Work With Me** | The 3 service packages with pricing |
| **Learn AI** | FAQ section for visitors curious about AI |
| **How It Works** | 4-step process from discovery call to handover |
| **CTA Banner** | Full-width call to action |
| **Contact** | Discovery call booking form + direct email |
| **Footer** | Brand, contact, and copyright |

---

## Services

| Package | Price | Description |
|---|---|---|
| The AI Kickstart | From R500 | Learn the basics of AI for your business |
| The Auto Admin | From R2,500 | Custom 24/7 AI workflow + 30 days support |
| The Freedom System | From R5,500 | Full operational overhaul, 5+ hours/week reclaimed |

---

## Tech Stack

- **HTML5** — single file, no framework
- **CSS3** — custom properties, grid, flexbox, animations
- **Vanilla JavaScript** — scroll reveal, nav behaviour, active link highlighting
- **Fonts** — DM Serif Display, Cormorant Garamond, DM Sans via Google Fonts
- **Form** — Formspree (`https://formspree.io/f/xwvwpqvo`)
- **Hosting** — GitHub Pages

---

## How to Update the Site

### 1. Edit the file
Open `index.html` in any text editor (VS Code recommended).

### 2. Key things you may want to update

**Pricing** — search for `R500`, `R2,500`, `R5,500` and update as needed

**Contact email** — search for `sebworks7@gmail.com`

**WhatsApp number** — search for `wa.me/27664505196`

**Your photo** — the photo is embedded as a base64 string. To replace it:
- Convert your new photo to base64 at [base64.guru/converter/encode/image](https://base64.guru/converter/encode/image)
- Search for `data:image/jpeg;base64,` and replace the string that follows

**Services copy** — search for `svc-name` to find service card titles

### 3. Upload to GitHub
- Go to your repository on github.com
- Click **Add file** → **Upload files**
- Upload the updated `index.html`
- Click **Commit changes**
- The live site updates within 60 seconds

---

## Form Setup

The contact form uses [Formspree](https://formspree.io).

- **Endpoint:** `https://formspree.io/f/xwvwpqvo`
- **Receives:** Name, Business, Email, WhatsApp, Industry, Message
- **Sends to:** sebworks7@gmail.com
- **Subject line:** New SEBWORKS Discovery Call Request
- **Redirect after submit:** sebworks.github.io

To change the notification email, log into formspree.io and update the form settings.

---

## Custom Domain (Optional)

To use `sebworks.co.za` instead of `sebworks.github.io`:

1. Buy the domain from [Domains.co.za](https://www.domains.co.za)
2. Go to **Settings → Pages → Custom domain** in this repository
3. Enter `sebworks.co.za` and click Save
4. At your domain registrar, add a **CNAME record**:
   - Name: `www`
   - Value: `sebworks.github.io`
5. GitHub will automatically provision an SSL certificate

---

## Contact

**Sebenzile Gabone**
AI Automation Consultant · Pretoria, South Africa
sebworks7@gmail.com
+27 66 450 5196

---

*© 2025 SEBWORKS. All rights reserved.*
