# robertacutright.com

The site for [robertacutright.com](https://robertacutright.com), a one-page
site for a hair stylist working from a private studio in Tacoma.

## What is in here

```
index.html      the whole site, 308 lines
logo.jpg        the RC logo
logo2.jpg       alternate mark
docs/plans/     notes on changes before they were made
CLAUDE.md       working notes for this repo
```

No build step, no framework, no dependencies. Fonts are Cinzel and Montserrat
from Google Fonts. Everything else is local.

Open `index.html` in a browser. That is the whole development loop.

## Deploying: a push publishes

**This repo is git-connected to Cloudflare Pages.** Pushing to `main` deploys
the live site automatically. There is no separate release step and no
confirmation, so a commit pushed here is a commit the public sees.

Every other Pages project here is direct-upload, where a push is harmless and
`wrangler` does the publishing. This one is the exception, which is exactly why
it is worth the heading.

## Services and prices live on the page, not here

An earlier version of this README listed the price list, the contact details and
a description of the logo image. By 2026-09-21 it had drifted: highlights had
moved from $170 to $175, vivid colour from $215 to $220, several services were
missing, it still carried a phone number the page no longer shows, and it
claimed SEO structured data the page does not have.

`index.html` is the source for all of that. This file describes the repo.
