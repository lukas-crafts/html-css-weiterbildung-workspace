# CSS Classes

Classes are the most flexible and common way to apply styles in CSS. Unlike IDs, which can only be used once per page, **classes are reusable**.

## Why use Classes?
- **Reusability**: Apply the same look to multiple elements (e.g., `.button`).
- **Separation of Concerns**: Keep your HTML focused on structure and your CSS on styling.
- **Maintainability**: Changing a single class rule updates all elements that use it.

## Syntax

### HTML
Add the `class` attribute to any tag:
```html
<p class="intro-text">This is a paragraph.</p>
<button class="btn btn-primary">Click Me</button>
```

### CSS
Target the class with a dot (`.`) prefix:
```css
.intro-text {
  font-size: 1.25rem;
  color: #333;
}

.btn {
  padding: 0.5rem 1rem;
  border-radius: 4px;
}
```

## Best Practices

1. **Naming**: Use descriptive names (e.g., `.card-header` instead of `.red-box`).
2. **Combine Classes**: Use a "base" class for common styles and "modifier" classes for specific variations.
   - Example: `<button class="btn btn-large">`
3. **Naming Conventions**: In the `site/` demo, we use a simple **BEM-lite** notation:
   - `.site-nav` (Block)
   - `.site-nav__links` (Element inside the block)
   - `.button--primary` (Modifier)

## 🚀 Try It Yourself

1.  Open **[exercises/lesson-d1/index.html](../exercises/lesson-d1/index.html)**.
2.  Add a custom class (e.g., `class="highlight"`) to one of the paragraphs.
3.  Then, open **[exercises/lesson-d1/style.css](../exercises/lesson-d1/style.css)** and add a `.highlight` rule to see it change!
