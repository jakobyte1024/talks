# s10yo11y slides

## Start

```bash
npm install
npm run dev
```

## Build

```bash
npm run build
```

The entrypoint for the deck is `slides.md`.

## Two-column content slides

This deck uses only Slidev built-in layouts.
Regular content slides that need two columns use the built-in `two-cols` layout explicitly.

Use the right column when needed with slot sugar:

```md
---
layout: two-cols
---

# Slide title

- Left side content
- More bullet points

::right::

![Architecture](./images/architecture.png)
```

Code snippets work the same way:

```md
# Example

- Explain the setup

::right::

~~~ts
const service = "dynatrace"
~~~
```
