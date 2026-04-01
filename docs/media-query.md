# Media Queries (Responsive Design)

Media Queries are a key part of Responsive Design. They allow you to apply different styles depending on the device's characteristics, like screen width or orientation.

## Mobile-First Design

A common and recommended approach is to write the styles for small screens first (outside of any media query) and then use media queries to add "layers" for larger screens.

```css
/* Base styles (Mobile) */
body {
  font-size: 16px;
}

/* Tablet / Desktop styles */
@media (min-width: 768px) {
  body {
    font-size: 18px;
  }
}
```

## Logic Operators

- `min-width`: Applies when the screen is *at least* this wide.
- `max-width`: Applies when the screen is *at most* this wide.
- `and`: Combine multiple conditions.

## 🚀 Try It Yourself

1.  Open **[site/style.css](../site/style.css)**.
2.  Find the `@media (min-width: 600px)` section.
3.  Change the value to `900px` and see how it affects the desktop layout in your browser!