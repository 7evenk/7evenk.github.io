# Google Tasks Filter website pages

Task: Add the new extension to the existing 7evenk Tools website, 2026-10-14.

## Prepared pages

- English product page: `/google-tasks-filter.html`
- German product page: `/de/google-tasks-filter.html`
- English privacy statement: `/google-tasks-filter-privacy.html`
- German privacy statement: `/de/google-tasks-filter-privacy.html`
- Product cards in both home pages, collection structured data and sitemap entries.

Reuse the shared styles and a product-specific blue accent. The icon comes from extension v0.5.0. The screenshot uses the actual runtime controls on a synthetic fixture; it contains no personal task data.

## Publication status

Extension version 0.5.0 is a development build. No Store URL or public source link is advertised. The extension repository is private. Publishing these website pages does not publish the extension.

Before announcing availability, verify the unpacked extension in Chrome and Edge. After confirmed Web Store publication, add the real installation/support links, developer contact, current release status and any updated privacy details in both languages.

## Verification

Check local asset/page/anchor links, JSON-LD and sitemap XML. Inspect product and privacy pages in desktop and 390px mobile layouts, language switching, navigation and sample image loading. Keep unrelated website files unchanged.

Version 0.5.0 uses header search and an overlaid control/results dropdown below the header field. The demo screenshot shows this layout with synthetic data. Search updates immediately on input; narrow headers move the field into the dropdown.

Issue: https://github.com/7evenk/google-tasks-filter/issues/1. Version 0.5.0 adds subtle original-row match outlines during search and an eight-second target frame after a jump, dismissible with Escape. Future changes are tracked with GitHub Issues.
