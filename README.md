# 🚀 Animated Services Section (GSAP + Tailwind-Inspired)

A modern, responsive **Services Section** built with HTML, CSS, and GSAP animations.  
Cards animate in on scroll with smooth effects (left/right slide + fade).  
Includes **Remix Icons** and is optimized for mobile responsiveness.  

---

## ✨ Features
- 📱 **Responsive design** (desktop → mobile friendly)  
- 🎞️ **GSAP + ScrollTrigger animations** (slide & fade on scroll)  
- 🎨 **Custom styled cards** with hover lift effect  
- 🔄 **Dark + light variants** for alternating cards  
- 🔗 Built-in **Remix Icons** integration  

---

## 🗂 Structure
```plaintext
services-section.html   # Main component file
assets/
   └── remove background fr.png   # Placeholder images
```

---

## ⚙️ How to Use

### 1. Include Dependencies
Add **Remix Icons**, **GSAP**, and **ScrollTrigger** in your `<head>` or before `</body>`:

```html
<!-- Remix Icons -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.6.0/remixicon.css" crossorigin="anonymous" referrerpolicy="no-referrer" />

<!-- GSAP + ScrollTrigger -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.13.0/gsap.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.13.0/ScrollTrigger.min.js"></script>
```

### 2. Copy the Section
Paste the `<section class="services-section">...</section>` block into your HTML.

### 3. Adjust Images
Replace:
```html
<img src="assets/remove background fr.png" alt="SEO" />
```
with your own images.

---

## ▶️ Demo Behavior
- Cards **slide in from left or right** as you scroll down.  
- Hovering on a card **lifts it slightly** for interactivity.  
- Icons rotate smoothly on hover.  

---

## 📸 Preview
_Add screenshots or a GIF demo here._

---

## 📜 License
This project is released under the **MIT License**.  
Feel free to use & modify ✨  

---

## 👤 Author
Built with ❤️ by **Saad Shah**  
Happy to help you craft modern web components 🚀
