# future-flow Branding

```css
/* ============================================================
   BRAND — future-flow (Facebook)
   ============================================================ */

[data-brand="future-flow"] {
  --brand-primary: #0066CC;
  --brand-secondary: #00FF00;
  --brand-accent: #00FF00;
  --brand-bg: #0A0A1A;
  --brand-text: #E8E8F0;
  --brand-muted: #8888A0;
  --brand-font-heading: "Courier New", "SF Mono", monospace;
  --brand-font-body: "Courier New", "SF Mono", monospace;
  --brand-border: #00FF00;
  --brand-radius: 2px;
}

[data-brand="future-flow"] h1 {
  font-family: "Courier New", "SF Mono", monospace;
  font-size: 2rem;
  font-weight: 700;
  color: #00FF00;
  line-height: 1.15;
  letter-spacing: 1.5px;
  text-transform: uppercase;
}

[data-brand="future-flow"] h2 {
  font-family: "Courier New", "SF Mono", monospace;
  font-size: 1.375rem;
  font-weight: 700;
  color: #0066CC;
  line-height: 1.25;
  letter-spacing: 1px;
  text-transform: uppercase;
}

[data-brand="future-flow"] h3 {
  font-family: "Courier New", "SF Mono", monospace;
  font-size: 1.125rem;
  font-weight: 600;
  color: #00FF00;
  line-height: 1.4;
  letter-spacing: 0.5px;
}

[data-brand="future-flow"] p,
[data-brand="future-flow"] li {
  font-family: "Courier New", "SF Mono", monospace;
  font-size: 0.9rem;
  font-weight: 400;
  color: #E8E8F0;
  line-height: 1.8;
}

/* ============================================================
   SHARED UTILITY CLASSES
   ============================================================ */

.brand-card {
  background: var(--brand-bg);
  color: var(--brand-text);
  border: 1px solid var(--brand-border);
  border-radius: var(--brand-radius);
  padding: 1.5rem;
}

.brand-btn {
  background: var(--brand-primary);
  color: var(--brand-bg);
  border: none;
  padding: 0.5rem 1.25rem;
  border-radius: var(--brand-radius);
  font-family: var(--brand-font-body);
  font-size: 0.875rem;
  cursor: pointer;
}

.brand-btn:hover {
  opacity: 0.9;
}

.brand-heading {
  font-family: var(--brand-font-heading);
  color: var(--brand-primary);
  line-height: 1.2;
}

.brand-link {
  color: var(--brand-primary);
  text-decoration: underline;
  text-decoration-color: var(--brand-accent);
}

.brand-muted {
  color: var(--brand-muted);
}

.brand-accent {
  color: var(--brand-accent);
}

.brand-post {
  background: var(--brand-bg);
  color: var(--brand-text);
  border: 1px solid var(--brand-border);
  border-radius: var(--brand-radius);
  padding: 1.25rem;
  font-family: var(--brand-font-body);
  max-width: 600px;
}

.brand-post h3 {
  font-family: var(--brand-font-heading);
  color: var(--brand-primary);
  margin: 0 0 0.5rem;
}

.brand-post .meta {
  color: var(--brand-muted);
  font-size: 0.8rem;
}

.brand-hashtag {
  color: var(--brand-primary);
  opacity: 0.8;
  font-size: 0.8rem;
}
```
