# CSS Selectors & Cascading

## What are CSS Selectors?
CSS selectors are patterns used to select HTML elements and apply styles to them.

### Common Selectors
- **Element selector** → `p`, `div`
- **Class selector** → `.box`
- **ID selector** → `#main`
- **Universal selector** → `*`
- **Attribute selector** → `input[type="text"]`

---

## What is Cascading?
Cascading means when multiple CSS rules target the same element, the browser decides which rule wins based on:

1. Specificity
2. Source order
3. Importance (`!important`)

---

## CSS Specificity (Priority Order)

From lowest → highest:

| Selector Type | Example | Priority |
|--------------|--------|----------|
| Universal | `*` | 0 |
| Element | `p` | 1 |
| Class | `.text` | 10 |
| ID | `#title` | 100 |
| Inline | `style=""` | 1000 |
| `!important` | Overrides all | 🔥 |

➡ Higher specificity overrides lower ones.

---

## Inheritance
- **Inherited properties**: `color`, `font-family`
- **Not inherited**: `margin`, `padding`, `border`
