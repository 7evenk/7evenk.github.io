# Album Sorter website addition

Requested on September 13, 2026: add an English product page and a public privacy notice for Album Sorter for OneDrive, using the existing GitHub Pages website.

- Product: `onedrive-album-sorter.html`
- Privacy notice: `onedrive-album-sorter-privacy.html`
- Product stylesheet: `album-sorter.css`
- Assets: `images/album-sorter-*`

The product is marked Coming soon until its store listing is publicly available. Do not advertise an install link before checking publication. The extension repository remains private and is not used as a public support destination. The website does not display a developer email address. Support is directed to the Chrome Web Store; confidential inquiries should use the developer contact details provided there. Install and support controls remain explicitly unavailable until the listing is published. Once it is public, replace the disabled install buttons with its verified URL and enable the support link after checking support visibility.

The promotional illustration was generated using Imagegen for the extension project. The demo screenshot uses fictional album names, counts and illustrations with the real controls. No private album photographs or account screenshots were copied. See the extension repository's `assets/store/README.md` for provenance and reproduction details.

Local verification: product page and privacy notice rendered in the browser; image loads, privacy navigation and viewport overflow checked. No extension behavior changes are included here. The existing GitHub Pages hosting is retained; no additional hosting service, tracking, external fonts or scripts are introduced.

Publishing requires a fine-grained PAT scoped specifically to `7evenk/7evenk.github.io`, stored only in Git Credential Manager through Agent Foundation's `tools/codex-github-bootstrap.ps1`. GitHub CLI calls must use `tools/gh-repo.ps1`. The repository-specific credential was configured through the bootstrap and repository access was verified before publication. Verify the public URLs after the GitHub Pages deployment completes.
