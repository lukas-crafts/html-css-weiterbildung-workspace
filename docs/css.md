# CSS Fundamentals

CSS (Cascading Style Sheets) is the code that styles web content. This page explains the core principles of how CSS behaves.

## The Cascade

The "C" in CSS stands for **Cascading**. It means that rules at the bottom of the style sheet generally override rules at the top if they have the same priority.

## Specificity

Specificity is how a browser decides which CSS property value is most relevant to an element.

1.  **Inline styles** (e.g., `style="color:red"`) - Highest priority.
2.  **IDs** (e.g., `#header`)
3.  **Classes, Attributes, Pseudo-classes** (e.g., `.btn`, `[type="text"]`, `:hover`)
4.  **Elements** (e.g., `h1`, `div`, `p`) - Lowest priority.

*Rule of thumb: Always prefer classes (e.g., `.btn`) over IDs and inline styles for cleaner, more reusable code.*

## Inheritance

Some CSS properties inherit their values from their parent (e.g., `font-family`, `color`), while others don't (e.g., `border`, `margin`).

## 🚀 Try It Yourself

1.  Open **[exercises/lesson-d1/style.css](../exercises/lesson-d1/style.css)**.
2.  Find the `h1` or `p` elements and add a `color` property.
3.  Try to override it by creating a custom class (e.g., `.red-text`) and applying it to the HTML.