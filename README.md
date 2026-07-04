# Software Development Life Cycle (SDLC)

[![Documentation](https://github.com/johnaoga/gl-sdlc/actions/workflows/docs.yml/badge.svg)](https://github.com/johnaoga/gl-sdlc/actions/workflows/docs.yml)

Course notes for Software Development Life Cycle at IFRI/UAC Benin (in French).

📖 **Documentation**: [View on GitHub Pages](https://johnaoga.github.io/gl-sdlc/)

## Pull Request Preview

Every pull request automatically gets a live preview deployed to GitHub Pages.
The `docs.yml` workflow posts a comment on the PR with a direct link once the build completes.

Preview URL pattern:
```
https://johnaoga.github.io/gl-sdlc/pr-preview/pr-<number>/
```

The preview is removed automatically when the PR is closed or merged.

> **One-time setup** (repository maintainer): GitHub Pages must be configured to deploy from the `gh-pages` branch (root).  
> Go to **Settings → Pages → Source** and select **Deploy from a branch → gh-pages / root**.

## Local Development

```bash
cd docs
pip install -r requirements.txt
sphinx-build -b html source _build/html
# Open _build/html/index.html in browser
```
