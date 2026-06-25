# Hellyeah Pitch Deck

HTML version of the Hellyeah revenue-first user acquisition pitch deck.

## Preview

Open `index.html` directly, or run:

```bash
npm run preview
```

Then open:

```text
http://localhost:3000
```

The one-pager version is available at:

```text
one-pager/index.html
```

Copy-ready one-pager text is available at:

```text
one-pager/one-pager-copy.md
```

## Edit workflow

The source of truth is:

```text
src/build-hellyeah-html-deck.mjs
```

After editing, regenerate the deck:

```bash
npm run build
```

This rewrites:

```text
index.html
preview-slide-01.html ... preview-slide-13.html
assets/
```

## Deploy

The project is static. Vercel can deploy the repository root directly.
