# 🌐 Web Practice

A collection of **single-file frontend pages** — each page is one `.html` file with
inline CSS and JavaScript. No build tools, no dependencies, no folders. Just open
a file and it works.

## 📄 Pages

| # | Page | File | Description |
|---|------|------|-------------|
| 01 | Login Page | [`login-page.html`](login-page.html) | Login form with validation & show/hide password |
| 02 | Landing Page | [`landing-page.html`](landing-page.html) | Hero, features grid & CTA banner |
| 03 | Navbar | [`navbar.html`](navbar.html) | Responsive navigation bar with hamburger menu |
| 04 | Calculator | [`calculator.html`](calculator.html) | Working calculator with JS logic |
| 05 | To-Do App | [`todo-app.html`](todo-app.html) | Add, complete and delete tasks |

>  Open [`index.html`](index.html) for a homepage that links to every page, with live search.

## 🗂️ Structure
web-practice/
├── index.html ← homepage / menu of all pages
├── login-page.html
├── landing-page.html
├── navbar.html
├── calculator.html
├── todo-app.html
└── README.md



**Rules for this repo:**
- ✅ Each page = **exactly one `.html` file**
- ✅ CSS goes in a `<style>` tag — JS in a `<script>` tag, in the same file
- ✅ Flat structure — no subfolders, no separate `.css` / `.js` files
- ✅ Lowercase file names with dashes (`todo-app.html`, not `ToDo App.html`)

##  View locally

Just open `index.html` in your browser, or use a simple local server:

```bash
# Python
python -m http.server 8000

# Node.js
npx serve
