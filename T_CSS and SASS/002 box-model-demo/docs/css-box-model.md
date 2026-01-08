# 📦 CSS Box Model Explained

The **CSS Box Model** defines how every HTML element is structured and how space is calculated around it.

---

## 🧱 Layers of the Box Model

Every element is made up of four layers:

- **Margin**  
  Space outside the element, creates distance from other elements.

- **Border**  
  Wraps around padding and content, has thickness, style, and color.

- **Padding**  
  Space inside the element, between content and border, increases the element’s visible size.  
  Example: `padding: 20px;`

- **Content**  
  The actual content of the element (text, image, etc.), controlled by width and height.

---

## 📐 Total Size Formula

Total width =
content width + left/right padding + left/right border + left/right margin


---

## ⚙️ box-sizing Property

- **Default:** `box-sizing: content-box;`  
- **Better practice:** `box-sizing: border-box;`

✔ Makes width include padding and border  
✔ Easier layouts

---

## 🎯 Learning Outcome

- Understand the four layers of the CSS Box Model  
- Learn how padding, border, and margin affect element size  
- Use `box-sizing: border-box` for simpler, predictable layouts
