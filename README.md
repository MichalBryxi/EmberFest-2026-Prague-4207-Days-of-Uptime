# 4,207 Days of Uptime

Slide deck for **"4,207 Days of Uptime: Evolving an Ember App Without a Rewrite"**,
a talk by [Michal Bryxí](https://mastodon.world/@MichalBryxi) at
[EmberFest 2026](https://emberfest.eu), Prague — September 17, 2026.

The talk walks through eleven years of evolving a single production Ember
app (a salon-management SaaS) without ever rewriting it from scratch, and
the practices that made that possible: fullstack ownership, keeping the
data model as the source of truth, one pattern per concern, and treating
automation as a standing investment rather than a distraction.

📄 [Download the slides as PDF](slides-export.pdf)

Built with [Slidev](https://sli.dev).

## Development

```sh
pnpm install
pnpm dev       # dev server with hot reload, http://localhost:3030
```

Edit [`slides.md`](slides.md) — changes show up instantly.

## Building

```sh
pnpm build     # static site
pnpm export    # PDF export (slides-export.pdf)
```

## Structure

```
slides.md              deck content
style.css               "Sunburst" theme: parchment content slides, deep-plum
                         chapter breaks, a five-color rotating accent, JetBrains
                         Mono throughout
layouts/                custom Slidev layouts (image-right-narrow: 65/35 split)
public/                 images used in the deck (photos, memes, screenshots)
CHANGELOG.md             history of changes to the deck
```

## License

Talk content and slide deck © Michal Bryxí. Third-party meme images belong
to their respective creators and are used under fair use for
commentary/illustration.
