# Document validation

Checked on 15 October 2026. Scope: HTML document and its browser interactions. No Android device runs or model performance benchmarks were performed.

- HTML: one H1, 15 sections, unique IDs and valid internal anchor targets.
- Runtime: all CSS and JavaScript inline; no external scripts or stylesheets.
- Examples: three Python snippets parse; two JSON examples and JSON-LD parse; inline JavaScript passes syntax checks.
- Responsive layout: no page-level horizontal overflow at 320, 390, 768, 1024 and 1440 CSS pixels. Wide tables and code use their own scroll regions.
- Calculator: default formulas checked; higher-cost/slower hybrid case, empty input validation, zero baseline cost and reset verified.
- Routing simulation: normal completion, unknown-state pause, failed assertion and reset verified. Stopped states disable advancement.
- Theme: manual toggle persists across reload; light and dark views inspected.
- Browser: no console errors or warnings observed during checks.
- Color tokens: sampled body text exceeds 7:1 contrast; input boundary tokens exceed 3:1 against adjacent surfaces in both themes. This is a token check, not a complete accessibility audit.
- Sharing asset: original 1200×630 PNG; no remote imagery.

Calculator values remain assumptions. Successful document checks do not establish speed, cost, accuracy or reliability of the proposed mobile runner.
