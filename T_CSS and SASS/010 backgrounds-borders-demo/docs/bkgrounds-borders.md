# 1️⃣ Explanation: Backgrounds & Borders (Beginner Level)

CSS allows you to **style the background and borders** of elements, making your page visually appealing.

---

## 🔹 1. Backgrounds

### Background color

```css
background-color: lightblue;
```

### Background image

```css
background-image: url('image.jpg');
background-size: cover;
background-repeat: no-repeat;
```

### Gradients (smooth color transitions)

CSS supports **linear** and **radial gradients**.

#### Linear gradient

```css
background: linear-gradient(to right, red, yellow);
```

* `to right` → left to right
* Colors blend smoothly

#### Radial gradient

```css
background: radial-gradient(circle, red, yellow);
```

* Colors radiate from the center

---

## 🔹 2. Border

The **border** wraps around an element. You can control:

* **Width**
* **Style** (solid, dashed, dotted, double)
* **Color**

```css
border: 3px solid black;
```

---

### Border Radius

Makes corners **rounded**:

```css
border-radius: 10px;
border-radius: 50%; /* For circular shapes */
```

---

## 🔹 3. Box Shadow

Adds **shadow effect** behind elements:

```css
box-shadow: 5px 5px 10px rgba(0,0,0,0.5);
```

* `5px 5px` → horizontal & vertical offset
* `10px` → blur radius
* `rgba(0,0,0,0.5)` → shadow color & opacity

---

## 🔹 Summary

* **Backgrounds:** colors, images, gradients
* **Borders:** width, style, color, rounded corners
* **Box-shadow:** adds depth and 3D effect

---

