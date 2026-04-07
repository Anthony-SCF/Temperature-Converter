# JavaScript Hands-On Project 2-1 — Temperature Converter

An interactive JavaScript web app that converts temperatures **between Fahrenheit and Celsius in real time**. Built as part of Chapter 2 coursework, demonstrating event handling, arithmetic expressions, and DOM interaction.

---

## Features

- **Bidirectional conversion:** Enter a value in either field and the other updates automatically
- **Fahrenheit → Celsius:** Uses the formula `(F - 32) / 1.8`
- **Celsius → Fahrenheit:** Uses the formula `(C * 1.8) + 32`
- **`onchange` event handling:** Conversion triggers when the user tabs out of a field — no submit button needed
- **Rounded output:** Results displayed to 2 decimal places using `.toFixed(2)`
- **Modern UI:** Centered card layout with blue-bordered fieldsets and clean typography

---

## Project Structure

```
JS-Temperature-Converter/
├── TemperatureConverter.html       # Temperature converter app (HTML + CSS + JS)
├── Reflection_Project2-1.docx      # Written reflection on concepts learned
└── README.md
```

---

## Technologies Used

- **HTML5** – Semantic `<article>`, `<form>`, `<fieldset>`, and `<input type="number">` elements
- **CSS3** – Flexbox centering, box shadow, border-radius, and responsive sizing
- **JavaScript** – `onchange` event handlers, arithmetic expressions, `toFixed()` formatting

---

## Concepts Covered

- `onchange` event handler for responsive input detection
- `document.getElementById()` for accessing and updating input values
- JavaScript arithmetic operators for formula-based calculation
- `.toFixed()` for numeric precision formatting
- Connecting HTML inputs to JavaScript logic without a form submission

---

## Reflection

> The most challenging part was correctly mapping the logic to the event listeners so that conversion happened automatically on Tab key press. It was very enjoyable to use arithmetic operators within JavaScript to solve a real-world problem like temperature scaling.

*See `Reflection_Project2-1.docx` for the full written reflection.*

---

## Author

**Anthony North**  
Date: February 4, 2026  
State College of Florida  
Course: Web Development / JavaScript  
Chapter: 2
