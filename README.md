# Makan-Mana-Melaka
# Makan Mana University (MMU) 🍔📱

A premium, minimalist, mobile-first single-page web application designed for university students to eliminate dinner-time indecision and gamify squad night outings. 

Live Link: [Launch MMU App](https://wde1113.github.io/Makan-Mana-Melaka/) *(Optimized for mobile viewports)*

---

## ✨ Features

### 1. 🃏 Food Card Deck (Dynamic Selector)
* **Smart Filtering:** Filter local dining hotspots by **Meal Time** (Dinner, Supper, Dessert), **Area** (Kota Laksamana, Malim, Klebang, MITC, etc.), and **Price Tier** (`$`, `$$`, `$$$`) using elegant, swipeable pill badges.
* **3D Card Flip:** Uses a hardware-accelerated 3D transform animation to draw a random restaurant matching your exact mood.
* **One-Tap Navigation:** Seamlessly pairs with native mobile mapping environments to launch route directions directly into Google Maps with a single click.

### 2. 🧾 Who Belanja? (Hidden Bill Roulette)
* **Attendance Checklist:** A touch-friendly grid interface to dynamically check/uncheck squad members based on who showed up to eat.
* **The Cloche Reveal:** Replaces standard boring spinners with an interactive Russian-roulette style table game. Friends take turns lifting their food trays to find out who is safe and who gets stuck with the hidden bill!
* **Squad Default Lineup:** Built-in attendance profiles for *Chloe Lau, Aqin, Bryan Ng, Ng Wei De, Yee Han Sen, Yan Yi Low, and Tan Rou Hui*.

---

## 🛠️ Tech Stack & Design Architecture

* **Frontend Wrapper:** Clean semantic HTML5 structure bundled as an SPA (Single Page Application).
* **Styling Engine:** Tailwind CSS via CDN using modern utility frameworks like `min-h-[100dvh]` to eliminate mobile browser address bar layout clipping.
* **Theme:** "Simple Modern Aesthetic" featuring an off-white canvas (`#F9F9FB`), deep charcoal typography (`#2D2D32`), fluid rounded profiles (`rounded-3xl`), and ultra-subtle ambient drop shadows.
* **State & Persistence:** Vanilla JavaScript (ES6+) managing localized application states paired with browser `localStorage` to ensure custom-added restaurants persist across sessions permanently.

---

## 🔒 Security & Deployment Notes

* **Client-Side Authorization Barrier:** To safeguard community-driven datasets while keeping host maintenance 100% free on GitHub Pages public repositories, a minimalist password gate overlay blocks unauthorized access until the global squad passphrase is key-validated.
* **Infinite Token Lifespan:** Authorized tokens are cached within local hardware registers so active group members experience a zero-latency, bypass-login launcher shortcut when launched straight from their smartphone's Home Screen.

---
*Created as an interactive software utility for university squad outings.*
