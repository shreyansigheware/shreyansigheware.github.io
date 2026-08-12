# shreyansigheware.github.io

My portfolio site — live at **https://shreyansigheware.github.io**

## How it works

One file: `index.html`. Plain HTML with the CSS inlined. No build step, no framework, no
dependencies. GitHub Pages serves it automatically from the `main` branch because the repo is
named `<username>.github.io`.

## How to change it

Edit `index.html` — on github.com directly, or locally then `git push`. Live within a minute or
two.

Two things worth keeping as they are:

- **The dark-mode block.** The colours are defined once as variables at the top, then redefined
  under `prefers-color-scheme: dark`. Change a colour in both places or the site breaks for half
  of visitors.
- **Nothing loads from another server.** No CDN fonts, no analytics, no external images. That's
  why it's fast and why it never breaks.

## When you ship something

Add a card to the *Learning in public* section:

```html
<div class="card">
  <div class="card-top">
    <h3>What it is</h3>
    <span class="status live">Live</span>
  </div>
  <p class="org">One line on what it does — <a href="URL">see it</a></p>
</div>
```

Use `class="status live"` once the artifact exists and is linked. Use `class="status"` while it
is still pending. Don't mark something live before the link works — the whole point of the site
is that the claims on it can be checked.
