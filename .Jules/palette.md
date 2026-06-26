## 2024-05-23 - [Accessibility: Labels & Focus States]
**Learning:** For projects without a build system or framework, accessibility must be manually integrated using semantic HTML and utility CSS classes like .sr-only for visual consistency. Restoring focus states with :focus-visible provides a cross-device accessible experience without cluttering the UI for mouse users.
**Action:** Always check for outline: none and missing form labels in static projects. Implement .sr-only as a standard utility.
