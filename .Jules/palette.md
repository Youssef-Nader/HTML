## 2024-05-15 - [Accessible Form Inputs & Global Focus States]
**Learning:** In static HTML/CSS projects, accessibility often suffers from the lack of semantic association between form inputs and labels, and the use of 'outline: none' which hides focus indicators for keyboard users.
**Action:** Always implement a '.sr-only' utility for accessible-hidden labels and use ':focus-visible' with a consistent theme color to provide clear visual feedback without compromising design. Ensure 'outline: none' is removed from all interactive elements to prevent suppression of these focus indicators.
