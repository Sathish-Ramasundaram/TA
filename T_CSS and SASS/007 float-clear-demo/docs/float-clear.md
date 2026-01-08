# 🧩 CSS Float & Clear (Legacy Layout Technique)

Before **Flexbox** and **Grid**, developers used **float** to create layouts like columns, images with text wrapping, etc.  
Today, float is considered a **legacy layout technique**, but it is still important to understand.

---

## 🔹 What is float?

The `float` property moves an element to the left or right of its container and allows other content to wrap around it.

👉 Think of it like this:  
Floating an element is like pushing it to one side and letting text flow around it.

# 🧩 Problem with Float (Important!)

When elements are floated:

- They are removed from normal document flow  
- The parent container collapses (height becomes zero)  

👉 This is why **clear** is needed.

---

## 🔹 What is clear?

The `clear` property tells an element:  
**“Do not sit next to floated elements.”**

clear: left;
clear: right;
clear: both;

## 🔹 clear: both (Most Common)

clear: both;

Moves element below floated elements
✔ Prevents layout breaking
✔ Used to fix parent height issues

---

## 🔹 Why Float Is Legacy
Hard to maintain

Causes layout bugs

Needs extra fixes (clear, clearfix)

Replaced by Flexbox & Grid

👉 Still used today mainly for:

Floating images in text

Legacy projects

