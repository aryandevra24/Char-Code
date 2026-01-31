# 🔤 Char Code

A simple and interactive webpage that shows the **key**, **keycode**, and **code** of any key you press on your keyboard — built using HTML, CSS, and JavaScript.

---

## 🚀 Demo

Try it out here:  
👉 [Char-Code on GitHub Pages](https://github.dev/aryandevra24/Char-Code/)

---

## 🧠 Features

- Displays:
  - The key pressed (`e.key`)
  - Its keycode (`e.keyCode`)
  - The event code (`e.code`)
- Clean and minimal UI
- Works instantly in any browser

---

## 🗂️ Project Structure

Char-Code/  
├── index.html # Main HTML file  
├── style.css # Styles for layout and table  
└── script.js # JavaScript logic for event handling

---

## 💻 How It Works

1. When you press any key, a JavaScript event listener (`keydown`) is triggered.
2. It dynamically updates the page with:
   - The key you pressed
   - Its numeric keycode
   - The event code
3. The table is created inside the `<p id="insert">` element using JavaScript.

---

