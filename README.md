# Software Development Life Cycle (SDLC)

[![Documentation](https://github.com/johnaoga/gl-sdlc/actions/workflows/docs.yml/badge.svg)](https://github.com/johnaoga/gl-sdlc/actions/workflows/docs.yml)

Course notes for Software Development Life Cycle at IFRI/UAC Benin (in French).

📖 **Documentation**: [View on GitHub Pages](https://johnaoga.github.io/gl-sdlc/)

## Pull Request Preview

For pull requests, the `docs.yml` workflow builds the documentation and uploads it as an artifact.

1. Open the PR's **Actions** run for `Build and Deploy Documentation`
2. Download the `docs-preview-pr-<number>` artifact
3. Open `index.html` from the extracted artifact to review the rendered site before merge

## Local Development

```bash
cd docs
pip install -r requirements.txt
sphinx-build -b html source _build/html
# Open _build/html/index.html in browser
```
