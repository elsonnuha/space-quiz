# Orbit Quiz

Orbit Quiz is a small, single-page space exploration quiz. Answer 10 questions, learn a fact with each response, and see your score and mission-complete reaction at the end. The interface adapts to your system's light or dark theme and works without a server or third-party dependencies.

## Run locally

Open `index.html` directly in a modern web browser. No installation or build step is required.

## GitHub Pages

The GitHub Actions workflow in `.github/workflows/deploy-pages.yml` checks the static site on pull requests to `main` and deploys it to GitHub Pages after changes are pushed to `main`. It copies `index.html` into the Pages artifact; there is no compilation or dependency installation.
