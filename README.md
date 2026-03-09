# Simple News Aggregator 092K

A repository to test GitHub automation for issue management.

## Localization

This repository now includes a minimal localization scaffold so the project can grow with multilingual support instead of keeping all user-facing copy in a single language.

### Supported locales

- `en` — English
- `es` — Spanish

### Translation files

Translation resources live under `locales/`:

- `locales/en.json`
- `locales/es.json`

Each file uses the same keys so localized strings stay in sync.

### Current keys

- `app.title`
- `app.description`
- `news.heading`
- `news.empty`

### Adding a new locale

1. Copy `locales/en.json` to `locales/<language>.json`.
2. Translate the values while preserving the keys.
3. Keep all locale files updated whenever a new key is added.

This resolves the initial localization gap tracked in the issue by establishing a consistent place and format for translated content.
