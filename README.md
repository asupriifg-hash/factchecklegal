# Legal Pages Source

This folder contains legal content intended for public hosting (for App Store metadata and in-app links).

Recommended hosting:
- GitHub Pages from this repository or a dedicated docs repository.

Target URLs configured in app:
- `https://tompik.github.io/factcheck/docs/legal/privacy.html`
- `https://tompik.github.io/factcheck/docs/legal/terms.html`
- `https://tompik.github.io/factcheck/docs/legal/fair-use.html`
- `https://tompik.github.io/factcheck/docs/legal/support.html`

Before App Store submission:
1. Publish these pages to public HTTPS URLs.
2. Confirm each URL responds with `200`.
3. Keep `ios/FactcheckApp/Sources/App/AppConfig.swift` synchronized with final URLs.
