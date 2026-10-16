# Google Tasks Filter website pages

Task: Add the new extension to the existing 7evenk Tools website, 2026-10-14.

## Prepared pages

- English product page: `/google-tasks-filter.html`
- German product page: `/de/google-tasks-filter.html`
- English privacy statement: `/google-tasks-filter-privacy.html`
- German privacy statement: `/de/google-tasks-filter-privacy.html`
- Product cards in both home pages, collection structured data and sitemap entries.

Reuse the shared styles and a product-specific blue accent. The icon comes from extension v0.5.2. The screenshot uses the actual runtime controls on a synthetic fixture; it contains no personal task data.

## Publication status

The owner confirmed publication of extension 0.5.2 on October 16, 2026. Public listing: https://chromewebstore.google.com/detail/google-tasks-filter/fklpjehchlecbjnjcmckldmklohnfdje. English/German product pages and collection pages advertise availability and Store install/support links. The extension repository remains private.

Publication was confirmed by the owner; this website update does not independently certify Chrome/Edge runtime behavior. Support and developer contact are available through the Store listing.

## Verification

Check local asset/page/anchor links, JSON-LD and sitemap XML. Inspect product and privacy pages in desktop and 390px mobile layouts, language switching, navigation and sample image loading. Keep unrelated website files unchanged.

Version 0.5.2 uses header search and an overlaid control/results dropdown below the header field. The demo screenshot shows this layout with synthetic data. Search updates immediately on input; narrow headers move the field into the dropdown.

Issue: https://github.com/7evenk/google-tasks-filter/issues/1. Version 0.5.0 adds subtle original-row match outlines during search and an eight-second target frame after a jump, dismissible with Escape. Future changes are tracked with GitHub Issues.

Issue #2: https://github.com/7evenk/google-tasks-filter/issues/2. Version 0.5.1 paints the complete inset frame above the native opaque task surface, preserving pointer access to task controls.

Issue #3: https://github.com/7evenk/google-tasks-filter/issues/3. Candidate 0.5.2 adds localized Store metadata and a voluntary support link. Product and privacy pages disclose this click-only navigation; the support anchor is support-development. Store submission remains pending.

Release availability update tracked in https://github.com/7evenk/7evenk.github.io/issues/6. The previously pending Store submission notes above are historical.
