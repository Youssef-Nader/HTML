## 2024-06-28 - Improving Form and Icon Accessibility
**Learning:** Purely visual forms with placeholders but no labels are inaccessible to screen readers. Similarly, icon-only links provide no context for assistive technology. Using `.sr-only` labels and `aria-label` attributes on links provides necessary context without altering the intended visual design.
**Action:** Always include associated `<label>` elements for form inputs and `aria-label` for icon-only interactive elements in all future UI tasks.
