# Accessibility Manual Test

Use this checklist for interactive frontend exercises before considering them complete.

## Keyboard

- Start with the address bar and reach the page controls using `Tab`.
- Confirm every interactive control receives visible focus.
- Activate buttons and links with the expected keyboard keys.
- Check that focus order follows the visual and reading order.

## Content

- Confirm controls have clear accessible names.
- Check that text remains readable at narrow viewport widths.
- Verify that status or feedback is understandable without relying only on color.

## Responsive behavior

- Test one narrow viewport and one desktop-sized viewport.
- Look for horizontal scrolling, clipped controls, and overlapping content.

## Regression note

When a manual check finds a problem, record the affected page, reproduction steps, expected behavior, and observed behavior so the next change can be verified against the same case.