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

I chose the `50rem` breakpoint for the hero layout because it provides enough space for the text and card to sit comfortably in two columns. Below that width, they stack vertically to prevent the content from feeling cramped.

### AI Disclosure

I used ChatGPT to clarify CSS Grid sizing, intrinsic layout behavior, and responsive breakpoints, and to suggest test cases. I wrote the code and tested the layout myself.
