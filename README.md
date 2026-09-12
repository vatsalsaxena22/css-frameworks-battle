# CSS Framework Battle ⚔️

Welcome to **CSS Framework Battle** — a comparative evaluation project showcasing how different modern CSS frameworks, component libraries, and utility-first styling systems handle layout, components, and design implementation under identical or similar design constraints.

---

## 📂 Project Structure

This repository contains standalone HTML files, each implementing the project layout using a distinct CSS framework or library:

* `index.html` — The primary landing/entry page or reference implementation.
* `bootstrap.html` — Built using **Bootstrap** (v5), leveraging pre-styled components, the responsive grid system, and utility classes.
* `tailwind.html` — Built using **Tailwind CSS**, demonstrating utility-first styling, rapid design composition, and custom responsive modifiers.
* `w3.html` — Built using **W3.CSS**, showcasing a lightweight, responsive, classless/class-based modern CSS framework without heavy JavaScript dependencies.

---

## 🚀 Getting Started

Since these are static HTML files, no complex build steps, package managers (`npm`/`yarn`), or backend servers are required to view them.

### Option 1: Direct Browser Preview
1. Clone or download this repository.
2. Double-click any of the `.html` files (e.g., `tailwind.html`, `bootstrap.html`) to open them directly in your default web browser.

### Option 2: Local Development Server (Recommended)
To prevent CORS or local asset loading quirks, use a local server like Python or Node.js:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (http-server)
npx http-server
```
Then navigate to `http://localhost:8000` in your browser.

---

## 📊 Comparison Matrix

| Framework / File | Core Philosophy | Bundle / Overhead | Customization Method | Best Suited For |
| :--- | :--- | :--- | :--- | :--- |
| **Bootstrap** (`bootstrap.html`) | Component-driven UI kit | Moderate (JS + CSS) | SASS variables, theme overrides | Enterprise dashboards, rapid admin panels |
| **Tailwind CSS** (`tailwind.html`) | Utility-first low-level CSS | Extremely low (Purged/JIT) | `tailwind.config.js` / CSS variables | Highly custom UI, modern landing pages, design systems |
| **W3.CSS** (`w3.html`) | Lightweight material design | Minimal (Pure CSS, 0 JS) | Inline styles, framework CSS overrides | Fast-loading simple sites, lightweight widgets |

---

## 🛠️ Tech Stack & Dependencies

* **HTML5** for semantic document structure.
* **CSS Frameworks (CDN-linked):**
  * Bootstrap v5.x
  * Tailwind CSS (Play CDN / Compiled)
  * W3.CSS Framework

---

## 🤝 Contributing

Contributions, framework additions, or layout improvements are welcome! Feel free to fork this repository, add a new framework file (e.g., `bulma.html`, `foundation.html`), and submit a pull request.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
