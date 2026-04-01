# The CSS Box Model

The Box Model is the foundation of CSS layout. Every element on a web page is represented as a rectangular box.

## Components of the Box Model

1. **Content**: The inner part where text and images appear (e.g., `width` and `height`).
2. **Padding**: Transparent space around the content, inside the border.
3. **Border**: A line that goes around the padding and content.
4. **Margin**: Transparent space outside the border, separating the element from others.

### Visual Representation
```text
+---------------------------+
|          Margin           |
|  +---------------------+  |
|  |       Border        |  |
|  |  +---------------+  |  |
|  |  |    Padding    |  |  |
|  |  |  +---------+  |  |  |
|  |  |  | Content |  |  |  |
|  |  |  +---------+  |  |  |
|  |  +---------------+  |  |
|  +---------------------+  |
+---------------------------+
```

## `box-sizing: border-box` (The Modern Standard)

By default, adding padding or a border increases the total size of an element. To keep the width and height predictable, we use:

```css
* {
  box-sizing: border-box;
}
```

This ensures that `padding` and `border` are included *within* the specified width and height, instead of expanding the box.

## 🚀 Try It Yourself

1.  Open **[exercises/lesson-d1/style.css](../exercises/lesson-d1/style.css)**.
2.  Find the `input` or `button` elements and experiment with `padding` and `border`.
3.  Use the **Browser DevTools** (F12) to see how the dimensions change on-the-fly.