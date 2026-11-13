# walkflow-app.github.io: build output, do not edit

Everything in this repository is written by the Pages workflow of
[walkflow-app/walkflow](https://github.com/walkflow-app/walkflow) (`.github/workflows/pages.yml`, `scripts/build-pages.mjs`)
and replaced, as one commit, on every deploy. A change made here is lost with the next release.

Change the product page in `site/` of walkflow-app/walkflow (commit type `docs(site)` or `chore(site)`), and the web app
in its `src/`. A ruleset lets only the deploy key push here.
