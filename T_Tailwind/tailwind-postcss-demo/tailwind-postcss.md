# TailwindCSS + PostCSS Overview

## TailwindCSS
TailwindCSS is a **utility‑first CSS framework**.  
Instead of writing custom CSS rules, you use pre‑built classes such as:

- `text-red-500`
- `bg-blue-200`
- `flex`
- `items-center`

---

## PostCSS
PostCSS is a tool that **processes your CSS before the browser sees it**.  
Think of it as a **CSS compiler**.

Tailwind is installed as a **PostCSS plugin**, which means PostCSS reads your:

```css
@import "tailwindcss";
```

and expands it into thousands of utility classes.

---

## Workflow

1. Write `@import "tailwindcss";` in your CSS file.
2. PostCSS + Tailwind generate a big `output.css` file containing only the classes you actually use (based on your HTML).
3. Link `output.css` in your HTML `<head>`.
4. Use Tailwind utility classes directly in your HTML tags.

---