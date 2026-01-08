Absolutely! Let’s create a **beginner-friendly guide** for **CSS Media Queries** (responsive design), with **runnable HTML/CSS code** and a **README** for VS Code.

---

# 1️⃣ Explanation: Media Queries (Responsive Design Basics)

Websites today need to **look good on different screen sizes**—desktop, tablet, mobile.
CSS **Media Queries** allow you to **apply styles conditionally** based on the **screen width, height, orientation**, or other device features.

---

## 🔹 What is a Media Query?

A **media query** checks the device or viewport size and applies CSS rules only if the condition is true.

### Basic syntax:

```css
@media (condition) {
  /* CSS rules go here */
}
```

---

## 🔹 Common Conditions

* **max-width:** apply styles when viewport width is less than or equal to a value
* **min-width:** apply styles when viewport width is greater than or equal to a value

### Examples

```css
/* For screens smaller than 768px */
@media (max-width: 768px) {
  body {
    background-color: lightblue;
  }
}

/* For screens larger than 1024px */
@media (min-width: 1024px) {
  body {
    background-color: lightgreen;
  }
}
```

---

## 🔹 Responsive Design Principle

* **Default styles:** for desktop (large screens)
* **Override styles:** inside media queries for smaller screens (mobile/tablet)

> “Mobile-first” design: define mobile styles first, then use `min-width` media queries for larger screens.

---

# One-Line Summary

> **Media queries let you apply CSS conditionally so your website looks good on all screen sizes.**

---

