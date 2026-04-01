# Flexbox

Flexbox (Flexible Box Layout) is a one-dimensional layout method for laying out items in rows or columns. It's powerful for creating flexible designs and aligning elements within a container.

## Main vs. Cross Axis

Understanding axes is the most confusing part of Flexbox, but it's essential for alignment.

1.  **Main Axis**: Usually horizontal (left to right) if `flex-direction: row`.
2.  **Cross Axis**: Usually vertical (top to bottom) if `flex-direction: row`.

## The Flex Container

To start using Flexbox, add `display: flex;` to the parent (container) element.

| Property | Description | Common Values |
| :--- | :--- | :--- |
| `flex-direction` | Set the main axis direction | `row` (horizontal), `column` (vertical) |
| `justify-content` | Align items along the **Main Axis** | `flex-start`, `center`, `flex-end`, `space-between`, `space-around` |
| `align-items` | Align items along the **Cross Axis** | `stretch` (default), `center`, `flex-start`, `flex-end` |
| `flex-wrap` | Prevent items from pushing out of the box | `nowrap` (default), `wrap` |
| `gap` | Spacing between items | Any length value (e.g., `1rem`, `20px`) |

## 🚀 Try It Yourself

1.  Open **[exercises/flexbox/style.css](../exercises/flexbox/style.css)**.
2.  Play with the `flex-direction` and `justify-content` values on the `.container` class.
3.  Add `flex: 1` to a `.item` to see it grow and fill the available space.
