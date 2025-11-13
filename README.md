# High‑impact upgrades for Jehovah’s View of Time

- **Typography and spacing**
  - Slightly increase line-height and refine spacing.
  - Consider a professional UI font (e.g., Inter).

- **Visual hierarchy**
  - Add helper text/labels near inputs.
  - Emphasize primary vs. secondary buttons.

- **Buttons and focus**
  - Consistent hover/focus styles with visible focus rings.
  - Temporarily disable buttons during calculations.

- **Micro‑interactions**
  - Snappier transitions (≈200ms with easing).
  - Small success animation when results show.

- **Accessibility**
  - Add aria-live to result containers.
  - Explicit labels for inputs; keep contrast AA+.

- **Validation UX**
  - Inline error text (avoid alert) and keep focus in field.

- **Edge case hints**
  - Note: “No year 0; 1 BCE is immediately before 1 CE.”

- **Copy consistency**
  - Standardize BCE/CE capitalization and phrasing.

- **PWA/performance**
  - Versioned cache name in service worker.
  - Offline fallback page/message.
  - Add a dedicated maskable icon later.

- **Meta/SEO and sharing**
  - Meta description.
  - Open Graph/Twitter tags (title, description, image).
  - Favicon 16/32px.

- **Code organization**
  - Extract CSS/JS to separate files.
  - Use addEventListener everywhere (no inline handlers).

- **Optional**
  - Install hint for Chrome/Edge (beforeinstallprompt).
  - Privacy-friendly analytics (Plausible/Umami).
