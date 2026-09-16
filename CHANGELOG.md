# Change Log

## [v0.1.0]

### Content

- Cover, "About Me" (countries + career timelines), a photo-scatter hobbies
  slide, a running "unicorn" audience game, the "How it started" chat
  reenactment, size stats, the "kasa" word cloud + screenshot, and a
  2015-vs-2026 stack comparison.
- "Breaking the kingdom": a three-step animated Mermaid diagram
  (`PM -> Design -> {DB -> Backend, Frontend} -> User`) that evolves from a
  clean pipeline, to chaotic ad-hoc communication (dashed ❗ arrows), to a
  fully walled-off org chart (🧱 bricks) - node/arrow positions stay fixed
  across all three steps.
- "Data is king", "KISS data", "Pattern (singular)" and its `<DataGrid>`
  payoff (30/60/245 saved use-cases) cover the engineering principles
  behind eleven years without a rewrite.
- Closing "4,207 days later" slide, followed by a "Bonus unicorn round" of
  four off-topic hot takes for audience Q&A.

### Styling

- Custom "Sunburst" Slidev theme (`style.css`): warm parchment content
  slides, deep-plum chapter-break slides, a five-color rotating accent
  (magenta/orange/gold/teal/violet), JetBrains Mono throughout.
- Custom `image-right-narrow` layout (65/35 content/image split).
- Loud blockquote styling: colored left border, matching text color, bold.

### Infra

- Slidev + Vite dev server, PDF export via `pnpm export`.
- `public/` holds only the images referenced from `slides.md`; `style.css`
  holds only selectors used by current slide content.
- Exported PDF (`slides-export.pdf`) committed and linked from the README.
- No dependencies beyond Slidev itself.
