# Astro Dynamic Event Engine 🚀

A modular web system built with **Astro** and **TypeScript** to generate interactive event invitations through structured data injection.

## 🎯 Project Overview
This project uses a template-based architecture. By separating the visual logic from the event data, I can deploy multiple unique invitations using a single core layout. 

## 🛠 Tech Stack
- **Framework:** Astro 5.0
- **Language:** TypeScript (Type-safe props)
- **Styling:** CSS3 with Dynamic Variables (`define:vars`)
- **Animations:** Native Scroll-Driven Animations

## ✨ Key Technical Features

### 1. Structured Data Management
The system uses a TypeScript interface to manage 30+ customization points. This ensures that every invitation has all required data (colors, dates, links) before building, preventing runtime errors.

### 2. High-Performance CSS
- **Dynamic Variables:** Uses Astro's `define:vars` to pass TypeScript values directly into CSS, allowing for custom themes without extra JavaScript.
- **Responsive Logic:** Includes a `clamp()` based scaling system that adjusts typography based on the length of the guest's name (`charCount`).
- **Scroll Effects:** High-performance animations using `animation-timeline`, reducing the need for heavy animation libraries.

### 3. User Experience
- Integrated WhatsApp API for RSVP.
- Optimized for mobile devices (Mobile-first).
- Dynamic countdown timer logic.

## 📂 Project Structure
- `/src/layouts/`: Core logic and styling.
- `/src/pages/`: Individual event data and implementation.
