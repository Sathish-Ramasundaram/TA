# 🧩 CSS z-index Property (Layering Elements)

The **z-index** property controls the vertical stacking order of elements when they overlap.

---

## 🔹 How z-index works
- Elements with a **higher z-index value** appear on top  
- Elements with a **lower z-index value** appear behind  
- `z-index` works **only on positioned elements**  

✔ The element must have:  
`position: relative | absolute | fixed | sticky;`

## 🔹 Default Behavior
- If no `z-index` is set, elements stack based on **HTML order**  
- Later elements appear on top  

---

## 🔹 Rules to Remember
- `z-index` only works on **positioned elements**  
- Higher value = closer to the viewer  
- Negative values push elements **behind**  
- Parent stacking context affects children  
