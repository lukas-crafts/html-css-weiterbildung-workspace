# The `gap` Property

The `gap` property provides a simple way to set the gutters (spacing) between items in a Flexbox or Grid layout.

## Why Use `gap`?

Instead of adding `margin` to every single item and then having to remove it from the last (or first) child, `gap` only adds space **between** the items.

### The old way (with margin):
```css
.container > *:not(:last-child) {
  margin-right: 1.5rem;
}
```

### The `gap` way (modern):
```css
.container {
  display: flex;
  gap: 1.5rem;
}
```

## `row-gap` and `column-gap`

You can also set the vertical and horizontal gaps separately:

```css
.container {
  display: flex;
  flex-wrap: wrap;
  row-gap: 1rem;
  column-gap: 2rem;
}
```

## 🚀 Try It Yourself

1.  Open **[exercises/flexbox/style.css](../exercises/flexbox/style.css)**.
2.  Add a `gap: 20px;` property to the `.container` to see how it adds space between items.
3.  Combine `gap` with `flex-wrap: wrap;` and see what happens!