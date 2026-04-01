# Inline-Level Elements

Inline elements are the counterpart to block-level elements. They are used for smaller pieces of content, often within a block-level element.

## Characteristics of Inline Elements

- They do **not** start on a new line.
- They only take up as much width as necessary for their content.
- They cannot have a specific `width` or `height` set (unless you change their `display` property).
- They only respect left and right margins/padding (top and bottom are ignored in the document flow).

## Common Inline elements

- `<span>`: A generic container for phrasing content (like a single word or phrase).
- `<a>`: An anchor link.
- `<strong>` and `<em>`: For bold and italicized text.
- `<img>`: An image.
- `<button>`: A clickable button.
- `<input>`: Form input fields.

---

## 🚀 Try It Yourself

1. Open **[exercises/lesson-d1/index.html](../exercises/lesson-d1/index.html)**.
2. Find a paragraph and wrap one word in a `<span>` tag.
3. Use the **Browser DevTools** (F12) to see how the span stays on the same line and only covers that specific word.
