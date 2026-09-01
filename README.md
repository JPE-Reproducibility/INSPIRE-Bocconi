# Reproducibility workshop INSPIRE Bocconi

This is the source code for the slide show for the reproducibility workshop at INSPIRE Bocconi. This will be shown alongside the repository at

https://github.com/floswald/ReproWorkshop

where the 10 commits correspond to the *10 steps* of the workshop.

Slides are published at https://JPE-Reproducibility.github.io/INSPIRE-Bocconi/

## How to build the slides

* Get [quarto](https://quarto.org/docs/get-started/) and compile.
* Deployment uses `quarto publish gh-pages` with local build - no CI needed.

## Yearly editions

The workshop runs once a year. `main` always holds the current edition, and the
published site always shows it - the URL above never changes.

Past editions are kept as git tags. After running the workshop:

```sh
git tag 2026
git push --tags
```

To look at an earlier edition: `git checkout 2026`.
