# Layout Systems Starter

Use this small page for Module 3 practice if you do not want to use your capstone yet.

## Files

- `index.html`: sample content with layout patterns.
- `styles.css`: starter CSS with tokens, layers, and layout prompts.

## Practice Goal

Build a responsive layout system:

- Flexible wrapper
- Intrinsic card grid
- Content-driven breakpoint
- Logical properties
- Container query component
- User-preference or feature query

## Practice Notes

### Intrinsic Layout

I used an intrinsic CSS Grid layout with `auto-fit` and `minmax()` so the guide cards adjust automatically to the available space. The grid changes the number of columns without requiring media queries.

### Breakpoint Decisions

- **50rem min-width (hero):** Switches the hero from a single column to two columns when there is enough space for the text and card to sit comfortably side by side.
- **40rem min-width (feature card):** Switches the feature card from a single column to two columns when its container is wide enough.
- **38rem max-width (feature card):** Adjusts the feature card's body padding in narrower containers to improve the visual alignment of the text beneath the image.

### AI Disclosure

I used ChatGPT to clarify CSS Grid sizing, intrinsic layout behavior, and responsive breakpoints, and to suggest test cases. I wrote the code and tested the layout myself.
