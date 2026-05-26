# Bankist Marketing Page 🌐

A modern, interactive landing page for the fictional "Bankist" banking application. This project showcases advanced DOM manipulation and modern UI components built with **Vanilla JavaScript**.

## ℹ️ About this Project

This is the second part of the Bankist project from **The Complete JavaScript Course** by Jonas Schmedtmann.
* **HTML & CSS**: Provided as starter code (design & layout).
* **JavaScript**: Written entirely by me.

My focus here was to build a highly interactive user interface using modern web APIs, focusing heavily on performance and event delegation.

## ✨ Features Implemented (JS)

* **Smooth Scrolling**: Implemented for navigation links using **Event Delegation** to attach a single event listener to the parent container, improving efficiency.
* **Sticky Navigation**: The navigation bar becomes fixed to the top of the screen once the user scrolls past the header, implemented performantly using the **Intersection Observer API**.
* **Reveal Sections on Scroll**: Sections smoothly fade and slide into view as the user scrolls down, using the Intersection Observer API to trigger CSS animations.
* **Lazy Loading Images**: High-resolution images are loaded only when they approach the viewport. This significantly improves initial page load time.
* **Tabbed Component**: An interactive "Operations" section where users can switch between different tabs of content.
* **Menu Fade Animation**: Hovering over a navigation link fades out the other links to draw focus.
* **Slider/Carousel Component**: A fully custom-built image/testimonial slider supporting:
  * Left and right arrow clicks.
  * Keyboard navigation (Left/Right arrow keys).
  * Interactive dot pagination.
* **Modal Window**: A popup window for account registration with smooth opening/closing functionality and "Escape" key support.

## 🛠 Technical Concepts Practiced

* **Intersection Observer API**: Used extensively for sticky nav, revealing elements, and lazy loading.
* **Event Delegation**: Optimizing event listeners by attaching them to common parent elements.
* **DOM Traversing**: Using methods like `.closest()`, `.querySelectorAll()`, and `.children` to navigate the DOM tree efficiently.
* **Data Attributes**: Reading from and writing to HTML `data-*` attributes to connect UI elements (like dots to slides).
* **CSS Custom Properties & Classes**: Manipulating CSS classes via JavaScript to trigger transitions and animations.

## 🚀 How to Run

1. Clone this repository.
2. Open `index.html` in your browser.
3. Scroll through the page to see the animations, lazy loading, and sticky navigation in action.

## 🌐 Live Demo
https://kyryl-h.github.io/banking-management/
