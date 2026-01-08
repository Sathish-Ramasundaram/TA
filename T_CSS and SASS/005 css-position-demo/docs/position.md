# CSS Position Property

The CSS `position` property controls how an element is placed in the document layout and how it responds to scrolling.

There are **five main position values**:

---

## 🔹 1. position: static (Default)
- Every element is `static` by default
- Positioned according to normal document flow
- `top`, `right`, `bottom`, `left` do not work


## 🔹 2. position: relative
- Positioned **relative to its normal position**
- Does **not** remove the element from the document flow
- Other elements are **not affected**
- Can be shifted using `top`, `right`, `bottom`, `left`

## 🔹 3. position: absolute
- Positioned **relative to the nearest positioned ancestor**
- Removed from the normal document flow
- If no positioned parent exists, it uses the `<body>` as reference
- Can be shifted using `top`, `right`, `bottom`, `left`

## 🔹 4. position: fixed
- Positioned **relative to the viewport**
- Stays in the same place even when scrolling
- Removed from the normal document flow
- Can be shifted using `top`, `right`, `bottom`, `left`

## 🔹 5. position: sticky
- Acts like **relative** until a scroll point is reached
- Then behaves like **fixed**
- Requires a `top`, `left`, etc. value to work
- Useful for headers, menus, or elements that should stay visible while scrolling



