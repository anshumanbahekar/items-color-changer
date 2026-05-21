# 🎨 Item's Colour Changer

One of my very first coding projects! I built this interactive web application back when I was in **5th class**, to learn the basics of **HTML, CSS, and JavaScript**. 

It’s a simple, colorful tool that lets you dynamically change the colors of various items (and a sneaky rocket, hahaha!). 

---

## Features

* **Interactive Selection:** Click on any item card (Backpack, Book, Pencil, etc.) to toggle its selection state.
* **Controls:** "Select All" or "Deselect All" items instantly with dedicated action buttons.
* **Color Panel:** Choose from 20 pre-defined color swatches or pick a unique shade using the custom color picker.
* **Fill Random:** Click "Fill Random" to let JavaScript generate random hex codes and automatically paint every item.
* **Reset:** Instantly revert all elements back to their default look.

---

## 🛠️ Concepts I Learned

Building this project helped me wrap my head around several core web development building blocks:

### 1. HTML & SVGs
* Structuring content with semantic tags.
* Working with scalable vector graphics (`<svg>`, `<rect>`, `<ellipse>`, `<polygon>`) and understanding how they are drawn inside a viewport.

### 2. Embedded CSS
* Using modern CSS features like CSS variables (`var(--...)`).
* Building responsive layouts using **CSS Grid** and Flexbox.

### 3. Beginner-Friendly JavaScript
* **DOM Manipulation:** Accessing and modifying HTML elements using `document.getElementById` and `document.querySelectorAll`.
* **Event Handling:** Attaching `onclick` and `oninput` events directly into the HTML.
* **State Management:** Using a JavaScript `Set()` object to remember exactly which items are currently selected.
* **Math & Functions:** * Using basic logic to break down Hex codes into RGB variables to dynamically apply authentic dark/light shading variations.
    * Generating strings using `Math.random()` to dynamically craft valid random color codes.

---

## 📁 Have a look - https://anshumanbahekar.github.io/items-color-changer/
