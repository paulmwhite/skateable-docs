# skateable-docs

Public documentation site for [Skateable](https://skateable.paulmwhite.com), served via GitHub Pages at `skateable.paulmwhite.com`.

## Pages

| Path | URL |
|------|-----|
| `index.html` | `/` — marketing landing page |
| `support/index.html` | `/support` — support & FAQ |
| `privacy/index.html` | `/privacy` — privacy policy |
| `disclaimer/index.html` | `/disclaimer` — disclaimer |

## Updating a page

1. Edit the relevant HTML file directly — there is no build step.
2. Commit and push to `main`:

```sh
git add <file>
git commit -m "your message"
git push
```

GitHub Pages deploys automatically from `main`. Changes are usually live within a minute.

## Adding a new page

1. Create a new directory (e.g. `terms/`) with an `index.html` inside it.
2. Follow the same HTML structure as an existing page for consistent styling.
3. Commit and push to `main`.

## Local preview

Open any `index.html` directly in a browser, or use a local server:

```sh
npx serve .
```
