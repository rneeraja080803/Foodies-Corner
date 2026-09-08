# 🍴 Foodies Corner — Taste the World 🌍

A responsive, single-page recipe & food-sharing website built with plain **HTML, CSS, and JavaScript** — no frameworks, no build tools.

## ✨ Features

- **Session-style login/logout** with real-time email format validation, strong-password rules (8+ chars, uppercase, lowercase, number, special character), and a show/hide password toggle
- **4 dynamic views** — Home, Suggestions, Recipes, Contact — swapped client-side via vanilla JS DOM manipulation (no page reloads)
- **Global recipe catalog** — 6+ dishes spanning Indian, Italian, Japanese, Mexican, Thai, and American cuisine, each with an expandable "View Recipe" panel (ingredients + steps) using native `<details>`/`<summary>`
- **Client-side validated suggestion form** with instant success confirmation
- **Fully responsive** — CSS Flexbox layout, mobile breakpoints, hover animations, and accessible focus states

## 🛠️ Tech Stack

- HTML5
- CSS3 (custom properties, Flexbox, media queries)
- Vanilla JavaScript (DOM manipulation, form validation, regex)

## 🚀 Running Locally

No build step required — it's a static site.

```bash
git clone https://github.com/<your-username>/foodies-corner.git
cd foodies-corner
# then just open index.html in your browser
```

Or serve it locally:

```bash
python3 -m http.server 8000
# visit http://localhost:8000
```

## 📸 Screenshots

### Home Page (Full View)
![Home Page Full](screenshots/home-full.png)

### Login Page
![Login Page](screenshots/01-login.png)

### Home Page
![Home Page](screenshots/02-home.png)

### Recipes Page
![Recipes Page](screenshots/03-recipes.png)

### Suggestions Page
![Suggestions Page](screenshots/04-suggestions.png)

### Contact Page
![Contact Page](screenshots/05-contact.png)

## 🖼️ Image Credits

The images shipped in this repo are lightweight placeholders generated for demo purposes. For production, swap them for free-to-use photos (same filenames: `login-bg.jpg`, `biryani.webp`, `indian.jpg`, `italian.jpg`, `pasta.jpg`, `burger.webp`, `sushi.jpg`, `tacos.jpg`, `butter-chicken.jpg`, `pad-thai.jpg`) from sources like [Unsplash](https://unsplash.com) or [Pixabay](https://pixabay.com) — both free for commercial use, no attribution required.

## 📁 Project Structure

```
foodies-corner/
├── index.html          # Full site (markup + styles + logic)
├── screenshots/         # App screenshots for this README
│   ├── 01-login.png
│   ├── 02-home.png
│   ├── 03-recipes.png
│   ├── 04-suggestions.png
│   └── 05-contact.png
├── login-bg.jpg
├── biryani.png
├── indian.png
├── italian.png
├── pasta.png
├── burger.png
├── sushi.png
├── tacos.png
├── butter-chicken.png
├── pad-thai.png
└── README.md
```

## 📄 License

This project is free to use for personal and educational purposes.
