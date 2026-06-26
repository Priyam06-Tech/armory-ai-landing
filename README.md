# Armory AI — Advanced Data Automation Platform

A high-performance, responsive SaaS landing page engineered for the "Next-Gen AI Platform Speed Run" hackathon.

## 📋 Project Overview
Armory AI is an advanced data automation platform. This landing page was built to showcase core platform capabilities, real-time system telemetry, and transparent scale modeling while adhering to strict performance and architectural constraints.

## 🛠 Tech Stack
* **Framework:** Vanilla JavaScript (No external frameworks/libraries).
* **Styling:** Tailwind CSS (via CDN).
* **Motion:** Native CSS transitions, Keyframes, and the Web Animations API (WAAPI).
* **Architecture:** Static HTML5/CSS3/JS.

## ✨ Key Features & Technical Compliance
* **Matrix-Driven Pricing:** Implemented a multi-dimensional pricing configuration matrix that computes values (INR, USD, EUR) dynamically without hardcoding. State updates are strictly isolated to localized DOM text nodes to ensure zero global re-renders.
* **Bento-to-Accordion Transition:** A responsive feature showcase that preserves the "active" context index when transitioning between desktop Bento-Grid and mobile Accordion layouts.
* **Performance:** Optimized for a <500ms initial orchestration timeline using GPU-accelerated CSS transforms and Intersection Observers for lazy-loaded scroll animations.
* **Semantic Integrity:** Built using strict semantic HTML5 tags (`<main>`, `<header>`, `<section>`, `<article>`) and valid metadata for SEO and accessibility.
* **Zero-Dependency Engine:** All UI components, charts, and motion logic were written from scratch to satisfy the project's "No External Component Library" requirement.

## 📦 Asset Compliance
* Used the provided color palette (Oceanic Noir, Nocturnal Expedition, Forsythia) and typography parameters (Inter, JetBrains Mono) as mandated by the project requirements.
