# GitHub Pages deployment

This package contains a one-page static site for `JinShuo-Li/Mathematical-Note`.

## Option A: Deploy through GitHub Actions

1. Copy `docs/index.html` into the repository at `docs/index.html`.
2. Copy `.github/workflows/pages.yml` into the repository at `.github/workflows/pages.yml`.
3. Commit and push:

```bash
git add docs/index.html .github/workflows/pages.yml
git commit -m "Add GitHub Pages landing page"
git push origin main
```

4. In GitHub: Settings -> Pages -> Build and deployment -> Source -> GitHub Actions.
5. Wait for the workflow named `Deploy GitHub Pages` to finish.

## Option B: Deploy from branch folder

1. Copy `docs/index.html` into the repository.
2. Commit and push it.
3. In GitHub: Settings -> Pages -> Build and deployment -> Source -> Deploy from a branch.
4. Select branch `main` and folder `/docs`.

## Notes

The page is static and has no external runtime dependencies. It preserves attribution and links to the CC BY-NC-SA 4.0 license.
