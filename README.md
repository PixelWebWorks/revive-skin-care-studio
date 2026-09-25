# Revive Skin Care Studio ✨

> Luxury High-Converting Landing Page with AI Voice & Chat Concierge for Revive Skin Care Studio in Stamford, CT.

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Ready-brightgreen)](https://pixelwebworks.github.io/revive-skin-care-studio/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)

---

## 🌟 Overview

A luxury web experience tailored for **Revive Skin Care Studio** (13 Spring St, 2nd Fl, Stamford, CT), showcasing their premier **90-minute Signature Revive Facial** ($225 / $195 with promo code `GLOW30`).

Designed to align seamlessly with social media advertising and convert visitors with interactive modalities, client testimonials, treatment reels, and an integrated **Bilingual AI Voice Concierge**.

---

## ✨ Features

- **Luxury Aesthetic & Typography**:
  - Color palette inspired by blush rose (`#f7aba9`), travertine stone, and warm neutrals.
  - Elegant typography featuring *Playfair Display*, *Italiana*, and *Plus Jakarta Sans*.
- **The 90-Minute Signature Facial Experience**:
  - Step-by-step breakdown of the 6 clinical modalities (Dermaplaning, Hyperbaric O2toDerm Oxygen Dome, Custom Peels, Ultrasonic Extractions, LED Waves, and Sculpting Massage).
  - High-resolution treatment imagery and 15 video demonstration reels.
- **Bilingual AI Voice & Chat Concierge**:
  - **Dynamic Language Detection**: Automatically adapts between English and Spanish based on what the client writes or speaks.
  - **Speech-to-Text & Text-to-Speech**: Integrated with Web Speech API and optional Google Cloud Text-to-Speech (*Neural2* / *Journey* voices).
  - **Google Gemini AI Brain**: Learns from `knowledge.js` clinical protocols, contraindications (Botox, pregnancy, rosacea), and pricing.
  - **Zero Cost Fallback Engine**: Local NLP knowledge engine ensures 100% uptime with $0 API dependencies.
  - **Cost Guardrails**: Built-in daily quota limits and session caps in local storage to prevent API bill shock.
- **Interactive Micro-Interactions**:
  - Live soundwave equalizer that animates during voice playback and speech input.
  - Confetti particle celebration when copying promo code `GLOW30`.
  - Floating concierge trigger aura and smooth modal transitions.
  - Direct Vagaro calendar integration for instant appointment bookings.

---

## 🚀 Quick Start

Simply open `index.html` in any modern web browser, or serve it locally:

```bash
# Using Python
python3 -m http.server 8080

# Using Node.js
npx serve .
```

Then visit `http://localhost:8080`.

---

## 📁 Project Structure

```
├── index.html          # Main landing page & Voice Concierge widget
├── knowledge.js        # Clinical knowledge base & FAQ data
├── assets/             # Logos, high-res treatment imagery, videos & thumbnails
├── .gitignore          # Git ignore rules
└── README.md           # Documentation
```

---

## 🌐 Deploy to GitHub Pages

To view the landing page live:

1. Go to your repository on GitHub: `https://github.com/PixelWebWorks/revive-skin-care-studio`
2. Navigate to **Settings** > **Pages**.
3. Under **Branch**, select `main` and `/ (root)`.
4. Click **Save**. Within minutes, your site will be live at:
   `https://pixelwebworks.github.io/revive-skin-care-studio/`

---

## 📞 Studio Details

* **Business:** Revive Skin Care Studio
* **Aesthetician:** Jennifer
* **Address:** 13 Spring St, 2nd floor, Stamford, CT 06901
* **Booking:** [Vagaro Official Calendar](https://www.vagaro.com/reviveskincarestudio/services)
* **Phone:** +1 (203) 391-4983

---

Developed by [PixelWebWorks](https://github.com/PixelWebWorks).
