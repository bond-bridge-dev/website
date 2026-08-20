```markdown
# Bond Bridge Website

A lightweight static site built with [MkDocs](https://www.mkdocs.org/) and the [Material](https://squidfunk.github.io/mkdocs-material/) theme.

## Project structure

```text
bond-bridge-site/
├── mkdocs.yml
├── .github/workflows/deploy.yml
└── docs/
    ├── index.md
    ├── services.md
    ├── case-studies.md
    ├── team.md
    └── bond-bridge-logo.svg
```

## Requirements

```shell
pip install mkdocs mkdocs-material
```

## Local preview

```shell
mkdocs serve
```

Open [http://127.0.0.1:8000](http://127.0.0.1:8000) in your browser. Pages auto-reload as you edit.

## Deploying the site

### Option A: Manual deploy via GitHub Actions (recommended)
1. Go to the repo on GitHub and click the **Actions** tab.
2. In the left sidebar, click **Deploy MkDocs site**.
3. Click the **Run workflow** dropdown button, leave the branch as `main`, then click **Run workflow** to confirm.
4. Watch the run in the list — a green checkmark means the site built successfully and was pushed to the `gh-pages` branch.

### Option B: Manual deploy via terminal

```shell
mkdocs gh-deploy
```

## Enabling GitHub Pages

1. Go to **Settings → Pages** in the repo.
2. Under **Build and deployment**, set the source to the `gh-pages` branch, `/ (root)` folder.
3. Save.

> Note: publishing Pages from a **private** repo requires GitHub Pro (personal) or GitHub Team+ (organization). On the free plan, the repo must be public for Pages to go live.

## Live site

```
https://bond-bridge-dev.github.io/website/
```

## Editing content

- **Home page:** `docs/index.md`
- **Services:** `docs/services.md`
- **Case Studies:** `docs/case-studies.md`
- **Team:** `docs/team.md`
- **Logo:** `docs/bond-bridge-logo.svg`
- **Nav / theme config:** `mkdocs.yml`
