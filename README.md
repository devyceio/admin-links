# Admin Links

Public JSON link lists for the app-switcher widget used across Devyce internal apps. Entries contain URLs, titles, and short tagline descriptions. Consuming apps infer icon locations from the services' base URLs.

## Files

- [test.json](test.json): links for the test environment.
- [prod.json](prod.json): links for the production environment.

Both files contain JSON arrays of entries with `title`, `description`, and `url` fields, in display order. Empty strings in `url` are placeholders for values that still need to be supplied. Coordinate the entry format with the consuming apps before using these lists.

## Public Data Only

Everything in this repository is public, even though the consuming apps are internal. Only publish information approved for public disclosure. Never include secrets, credentials, tokens, personal data, confidential information, or sensitive URL query parameters.

See [AGENTS.md](AGENTS.md) for contributor and coding-agent guidance.