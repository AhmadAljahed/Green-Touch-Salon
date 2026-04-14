# 🌿 Green Touch — Landing Page

A clean, RTL Arabic landing page for **Green Touch**, a beauty & care salon.  
Built with pure HTML & CSS — no frameworks, no dependencies.

---

## 📁 Project Structure

```
green-touch/
├── index.html          # Main HTML page
├── css/
│   └── style.css       # All styles (variables, layout, components, responsive)
├── assets/             # Place your images / favicon here
└── README.md
```

---

## ✏️ How to Customize

### 1. Update your WhatsApp number

Open `index.html` and find all occurrences of:

```
96500000000
```

Replace with your actual WhatsApp number (**no `+` sign, no spaces**).  
Example: `96512345678`

You can use your editor's **Find & Replace** (`Ctrl+H` or `Cmd+H`).

---

### 2. Edit services

Each service card is an `<article class="service-card">` block in `index.html`.  
Update the title, description, emoji icon, and WhatsApp pre-filled message as needed.

---

### 3. Change colors or fonts

All design tokens are in `css/style.css` under the `:root` block at the top:

```css
:root {
  --color-dark:  #183c2f;   /* primary dark green */
  --color-gold:  #d6b46c;   /* gold accent */
  --color-green: #25d366;   /* WhatsApp green CTA */
  /* ... */
}
```

Edit these values to rebrand the page instantly.

---

### 4. Add a favicon

Place your `favicon.ico` (or `.png`) inside the `assets/` folder, then uncomment this line in `index.html`:

```html
<link rel="icon" href="assets/favicon.ico" />
```

---

## 🚀 Deploying to GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Set source to the `main` branch, root `/`.
4. Your site will be live at:  
   `https://<your-username>.github.io/<repo-name>/`

---

## 🌐 Features

- ✅ Fully RTL (Arabic) layout
- ✅ Sticky navigation bar
- ✅ WhatsApp booking buttons (per service + global)
- ✅ Responsive — works on mobile, tablet, desktop
- ✅ CSS custom properties for easy theming
- ✅ Semantic HTML with ARIA labels for accessibility
- ✅ Smooth scroll & hover micro-interactions
- ✅ Zero JS, zero dependencies

---

## 📄 License

Free to use and modify for personal or commercial projects.

---

> Built with ❤️ for Green Touch Salon
