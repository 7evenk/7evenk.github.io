# Album Sorter website addition

Requested on September 13, 2026: add an English product page and a public privacy notice for Album Sorter for OneDrive, using the existing GitHub Pages website.

- Product: `onedrive-album-sorter.html`
- Privacy notice: `onedrive-album-sorter-privacy.html`
- Product stylesheet: `album-sorter.css`
- Assets: `images/album-sorter-*`

Version 0.1.3 was published on September 14, 2026. The public Chrome Web Store listing and its support-hub link were verified in the browser. English and German product pages now provide active install and support links. The extension repository remains private; public support uses the Chrome Web Store. No developer email address is displayed on this website.

The promotional illustration was generated using Imagegen for the extension project. The demo screenshot uses fictional album names, counts and illustrations with the real controls. No private album photographs or account screenshots were copied. See the extension repository's `assets/store/README.md` for provenance and reproduction details.

Local verification: product page and privacy notice rendered in the browser; image loads, privacy navigation and viewport overflow checked. No extension behavior changes are included here. The existing GitHub Pages hosting is retained; no additional hosting service, tracking, external fonts or scripts are introduced.

Publishing requires a fine-grained PAT scoped specifically to `7evenk/7evenk.github.io`, stored only in Git Credential Manager through Agent Foundation's `tools/codex-github-bootstrap.ps1`. GitHub CLI calls must use `tools/gh-repo.ps1`. The repository-specific credential was configured through the bootstrap and repository access was verified before publication. Verify the public URLs after the GitHub Pages deployment completes.

English and German product and privacy pages are available with matching EN/DE navigation links. The German homepage links to the German product page. The extension interface remains English. Language navigation, translated content, local links and the mobile layout were checked in the browser.
