# Changelog

## 1.0.0

- Initial stable release of `@aw-ng/icons`.
- Reusable `Icon` React component for rendering SVG icons consistently across applications.
- Component props: `name`, `color` (default `#000`), `size` (default `24`), `weight` (default `1`) and `containerStyle`.
- 395 icons across two styles: 208 outline and 187 solid variants, each addressable by name (e.g. `bell-outline`, `paragraph-solid`).
- Raw SVG source files for every icon, alongside a name-to-component mapping for icon lookup.
- Unit and snapshot tests for the `Icon` component (Jest).
- ESLint and Prettier configuration.
- CI and build workflows via GitHub Actions.
- README with installation, usage, props reference and contribution guide.
