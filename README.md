# Mobile Harness AI Provider Catalog

Remote overlay for the Mobile Harness Code central AI provider library.

`catalog.json` is a metadata-only document that adds new providers (or updates existing ones)
without shipping a new APK. The app verifies `catalog.json.sha256` before applying it and keeps the
bundled catalog as the base; this file can never remove a bundled provider or touch user API keys.

Format and publishing instructions: see `docs/AI_PROVIDER_LIBRARY.md` in `mobile-harness-code`.
