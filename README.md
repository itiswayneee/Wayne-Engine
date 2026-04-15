# Wayne Search

A sleek, modern search interface powered by **Google Programmable Search Engine**. This project features a "frosted glass" (glassmorphism) aesthetic, fully responsive design, and deep CSS overrides to ensure a seamless dark mode experience—even within Google's injected search results.

## ✨ Features

* **Glassmorphism UI:** Backdrop filters and translucent backgrounds for a high-end feel.
* **Dynamic Dark Mode:** Automatically adapts to the user's system settings using `@media (prefers-color-scheme: dark)`.
* **Deep CSS Injection:** Custom styles that override Google's default white backgrounds, even for autocomplete suggestions and pagination.
* **Responsive Grid:** Image search results that intelligently re-flow from 3 columns to 1 based on screen size.
* **Custom Scrollbars:** Themed scrollbars for a consistent look across the entire application.

---

## 🚀 Quick Start

### 1. Prerequisites
You will need a **Google Search Engine ID (CX)**. 
*The current code uses: `e44113464e8d747e9`*

### 2. Implementation
Copy the codeinto a file named `index.html` and open it in any modern web browser.

## 🛠 Customization

### Changing the Engine

To use your own Google Search Engine, replace the `cx` parameter in the script tag:

```
<script async src="[https://cse.google.com/cse.js?cx=YOUR_NEW_ID_HERE](https://cse.google.com/cse.js?cx=YOUR_NEW_ID_HERE)"></script>
```

### Color Palette

You can easily modify the primary theme by changing the CSS variables at the top of the <style> block:

| Variable | Light Mode (Default) | Dark Mode |
| :--- | :--- | :--- |
| `--bg-color` | `#f8f9fa` | `#0f172a` |
| `--text-primary` | `#4285f4` (Google Blue) | `#60a5fa` |
| `--card-bg` | `rgba(255, 255, 255, 0.8)` | `rgba(30, 41, 59, 0.7)` |
