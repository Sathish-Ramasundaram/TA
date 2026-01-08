
# 🚀 Project: `tailwind-postcss-demo`
---

This project demonstrates how to set up **TailwindCSS v4** with **PostCSS** from scratch.  
It is designed for beginners who want to understand how Tailwind works with PostCSS.

---

## 📂 Project Structure

```
tailwind-postcss-demo/
├── dist/               # Compiled CSS output
│   └── output.css
├── src/                # Source CSS
│   └── input.css
├── index.html          # HTML file using Tailwind classes
├── postcss.config.mjs  # PostCSS configuration
├── tailwind.config.js  # Tailwind configuration
└── package.json        # Project metadata + scripts
```

---

## 🚀 Setup Instructions

### 1. Create project folder
```bash
mkdir tailwind-postcss-demo
cd tailwind-postcss-demo
npm init -y
```

### 2. Install dependencies
```bash
npm install -D tailwindcss @tailwindcss/postcss postcss postcss-cli autoprefixer
```

### 3. Create config files
- `postcss.config.mjs`
```js
export default {
  plugins: {
    "@tailwindcss/postcss": {},
    autoprefixer: {},
  },
}
```

- `tailwind.config.js`
```js
/** @type {import('tailwindcss').Config} */
export default {
  content: ["./index.html"],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

### 4. Create input CSS
- `src/input.css`
```css
@import "tailwindcss";
```

### 5. Create HTML file (before build)
- `index.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Tailwind PostCSS Demo</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="dist/output.css" rel="stylesheet">
</head>
<body class="bg-gray-100 p-10">
  <h1 class="text-3xl font-bold text-red-500 text-center">
    Hello Sathish! This is red, bold, and centered.
  </h1>
  <p class="text-green-600 text-left mt-4">
    This is green and left-aligned.
  </p>
</body>
</html>
```

### 6. Add build scripts
In `package.json`:
```json
"scripts": {
  "build": "postcss src/input.css -o dist/output.css",
  "watch": "postcss src/input.css -o dist/output.css --watch"
}
```

### 7. Build CSS
```bash
npm run build
```

👉 This generates `dist/output.css` with only the classes used in `index.html`.

### 8. Run HTML
- Open `index.html` with **Live Server** in VS Code.  
- You should see:
  - A red, bold, centered heading.  
  - A green, left-aligned paragraph.  
  - A light gray background.

---

## 🛠 Development Workflow

- Run `npm run watch` to rebuild automatically when you save changes.  
- Use Tailwind utility classes directly in your HTML.  
- Tailwind will only generate the classes it finds in `index.html`.

---

## 🎯 Example Classes

- `text-red-500` → red text  
- `text-green-600` → green text  
- `text-center` → center align  
- `text-left` → left align  
- `font-bold` → bold text  
- `bg-gray-100` → light gray background  
- `p-10` → padding around the body  

---

