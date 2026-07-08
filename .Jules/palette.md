# Palette Agent UX Journal

This journal tracks critical UX and accessibility learnings.

## 2025-03-24 - Accessibility and Focus Indicators
**Learning:** Removing `outline: none` without providing a visible focus alternative makes the site inaccessible for keyboard users. Adding a global `:focus-visible` style ensures focus is only shown when relevant (e.g., keyboard navigation) and maintains visual polish.
**Action:** Always check for `outline: none` in CSS and provide a high-contrast `:focus-visible` alternative using the project's brand colors.
