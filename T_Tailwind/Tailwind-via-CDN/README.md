
# TailwindCSS CDN Demo

This project demonstrates how to use **TailwindCSS** directly via the CDN (Content Delivery Network) method.  
It requires no build tools, PostCSS, or configuration — just a single `<script>` tag in your HTML.

---

## 📂 Project Structure

```
Tailwind-via-CDN/
└── index.html
```

---

## 🚀 How It Works

1. **Include Tailwind via CDN**  
   Add the following line inside your `<head>`:
   ```html
   <script src="https://cdn.tailwindcss.com"></script>
   ```

   This loads TailwindCSS directly from the CDN.

2. **Write HTML with Tailwind classes**  
   Use Tailwind’s utility classes directly in your HTML tags.

---

## 🎯 What You’ll See

- A **large, bold, green heading** saying *Hello Tailwind!*  
- A **gray paragraph** below it with spacing (`mt-2`).  
- Padding (`p-6`) applied to the body.

---

## 🛠 When to Use CDN Method

- ✅ Quick demos and prototypes  
- ✅ Learning Tailwind basics  
- ✅ CodePen or small static HTML projects  

⚠️ **Not recommended for production** because:
- The CDN loads the entire Tailwind library (large file size).
- No purging of unused classes → slower performance.

---

