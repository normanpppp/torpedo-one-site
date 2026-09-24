# Torpedo One — mini site

Static site (HTML + CSS, no build step) rebuilt from the "Tor-One _ Sales Deck" Figma.
All images (hero background, catalogue artwork, Torpedo One logo, provider logos) were extracted from the Figma file into `assets/`.

## Publish on GitHub Pages
Double-click `deploy.command` (or run `./deploy.command` in Terminal).
- First run: signs you into GitHub if needed, creates a public repo `torpedo-one-site`, pushes, and turns on Pages.
- Later runs: commits and pushes your changes; the site updates within a minute.
- Custom repo name: `./deploy.command my-repo-name`
- Needs the GitHub CLI: `brew install gh`
