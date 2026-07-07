## 2024-05-15 - Accessibility Pattern: Global Focus States
**Learning:** Removing `outline: none` without providing a visible focus alternative is a common accessibility barrier. Using `:focus-visible` ensures that only keyboard users see the focus ring, maintaining design intent for mouse users while providing necessary feedback for accessibility.
**Action:** Always check for `outline: none` in CSS and replace it with a high-contrast `:focus-visible` style that uses the project's accent color.
