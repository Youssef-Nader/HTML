## 2025-05-14 - Accessible Form and Focus Pattern
**Learning:** This static portfolio used placeholders as the only way to label form inputs and had 'outline: none' on focus, making it inaccessible to screen readers and keyboard users.
**Action:** Always implement a '.sr-only' utility for semantic labels and a global ':focus-visible' style using the main theme color (var(--main-textColor)) to ensure accessibility without impacting the visual design for mouse users.
