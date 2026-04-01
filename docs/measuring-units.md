# Measuring Units in CSS

CSS offers many different units for measuring width, height, font size, and spacing. Choosing the right unit is critical for responsive and accessible design.

## Absolute Units

These units are fixed and will always look the same size relative to other fixed objects.

-   **`px` (Pixels)**: The most common absolute unit. It represents a single dot on the screen. Best for things that should not change size based on context (e.g., borders).

## Relative Units

These units are relative to something else (e.g., the parent element's size or the screen size).

| Unit | Relative to... | Use Case |
| :--- | :--- | :--- |
| `%` | **Parent element** | Great for layout (widths/heights). |
| `em` | **Own / Parent font-size** | Good for padding/margins around text. |
| `rem` | **Root font-size (<html>)** | **Best for accessibility** (font-sizes). |
| `vw` | **1% of Viewport Width** | Scale based on screen width. |
| `vh` | **1% of Viewport Height** | Scale based on screen height. |

## 🚀 Try It Yourself

1.  Open **[site/style.css](../site/style.css)**.
2.  Find the `font-size` properties and change them from `rem` to `px`.
3.  Think about how someone with a font size preference in their browser would be affected by this change.
