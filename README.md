# Date Tool Data

Remote data packages for Date Tool calendars, holidays, occasions, and school holidays.

Public manifest URL after GitHub Pages is enabled:

```text
https://mzare47.github.io/date-tool-data/manifest.json
```

The root `manifest.json` points to the latest compatible zip package. The app downloads the zip, verifies its SHA-256 checksum, extracts it, and validates the extracted JSON files using the manifest file declarations.

## Current test package

- Package version: `1.0.1-test1`
- Minimum supported app version: `1.0.0`
- Maximum supported app version, exclusive: `2.0.0`
- Data schema: `1`

## Files

- `manifest.json`: latest package pointer and compatibility metadata.
- `packages.json`: package history index for manual testing and rollback references.
- `packages/1.0.1-test1/manifest.json`: versioned package metadata.
- `packages/1.0.1-test1/date_tool_data_1.0.1-test1.zip`: versioned data package archive.