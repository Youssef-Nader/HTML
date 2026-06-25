## 2024-05-24 - [Accessible Form Fields with Custom Focus Rings]
**Learning:** This portfolio used placeholders as the sole means of labeling form fields and had `outline: none` on focus, which is a major accessibility barrier. A reusable pattern for this site is to add `sr-only` labels for screen readers and use the theme's `var(--main-textColor)` for high-visibility focus outlines with an `outline-offset` to ensure the indicator doesn't touch the input border.
**Action:** Always check for `outline: none` in forms and ensure every input has a linked `<label>`, even if visually hidden.
