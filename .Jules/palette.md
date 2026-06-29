## 2025-05-14 - Accessible Form and Social Media Enhancement
**Learning:** Icon-only links and form inputs without explicit labels are common accessibility barriers in static portfolios. Using `.sr-only` labels and `aria-label` attributes provides critical context for screen readers without altering the visual design. Global `:focus-visible` styles ensure keyboard users have clear visual feedback that matches the site's theme.
**Action:** Always include a `.sr-only` utility class and apply ARIA labels to decorative or icon-only interactive elements.
