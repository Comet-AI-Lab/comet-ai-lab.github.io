# CometAI Website

GitHub Pages website for CometAI - the organization homepage for HuggingFace and GitHub.

## Deployment to GitHub Pages

### Option A: Organization Site (cometai.github.io)

1. Create a new organization on GitHub called `CometAI` (or similar)
2. Create a repository named `cometai.github.io` (must match org name)
3. Push this website content to the repository
4. The site will be live at `https://cometai.github.io`

### Option B: Project Site (computationalgasdynamicslab.github.io/cometai)

1. Create a repository `cometai` under `ComputationalGasDynamicsLab`
2. Push website content to `main` branch in a `docs/` folder, or use `gh-pages` branch
3. Enable GitHub Pages in repository settings
4. Site will be at `https://computationalgasdynamicslab.github.io/cometai`

## Local Preview

```bash
cd website
python -m http.server 8080
# Open http://localhost:8080
```

## Files

- `index.html` - Main landing page
- `assets/logo.png` - CometAI logo (high-res)
- `assets/favicon.png` - Favicon for browser tabs
