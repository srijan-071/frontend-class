# frontend-class

A hands-on collection of frontend exercises and small UI builds.

## Focus

- Semantic HTML
- CSS layout with Flexbox and Grid
- Responsive interfaces
- JavaScript interactions
- Reusable UI patterns

## Approach

Each exercise is kept intentionally small so the implementation stays easy to inspect and improve.

```text
markup → layout → interaction → polish
```

## Run locally

Open the relevant HTML file in a browser, or serve the repository with any local static-file server when an exercise uses JavaScript modules or fetch requests.

## Exercise checklist

When adding or updating an exercise:

1. Keep the example focused on one frontend concept.
2. Prefer semantic HTML and controls that are usable with a keyboard.
3. Check the layout at both narrow and wide viewport sizes.
4. Avoid adding dependencies when plain HTML, CSS, or JavaScript is enough.
5. Check focus states and readable contrast when the example is interactive.

## Responsive check

Before considering an exercise complete, test at least one narrow viewport and one desktop-sized viewport. Look for horizontal overflow, clipped controls, and text that becomes difficult to read or operate.

## Accessibility check

For interactive exercises, test keyboard navigation from the beginning to the end of the page. Make sure focus remains visible and that controls have clear accessible names.

## Example: color grid

The color-grid exercise in `grid.html` uses native buttons so it can be operated with keyboard controls without additional JavaScript.
