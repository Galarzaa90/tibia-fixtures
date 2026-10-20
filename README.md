# tibia-fixtures

A collection of HTML pages and extracts from Tibia.com for testing parsers in any library, language, or framework.

Browse the [fixture catalogue](fixtures/README.md) for page types, edge cases, and historical layouts.

## Adding fixtures

- Add `.html` files to the matching category under `fixtures/`, copying the response exactly as served by Tibia.com. Do not format, reindent, trim whitespace, change encoding or line endings, or add a final newline.
- Update the catalogue and category count. Include a description and extraction date when known; otherwise leave the date blank.
- Avoid duplicates and keep useful historical cases under descriptive filenames.

HTML fixtures are excluded from Prettier and Git's text conversion. Exclude `fixtures/**/*.html` from any other formatter or automatic fixes, including formatting and whitespace cleanup on save.

## Licensing

Original contributions are dedicated under [CC0-1.0](LICENSE). Captured Tibia.com content is excluded; this dedication grants no additional rights over it. Adapted catalogue descriptions retain their Apache-2.0 licensing. See [third-party notices](THIRD_PARTY_NOTICES.md).
