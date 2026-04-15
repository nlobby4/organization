# Architecture

This repository is the canonical source for nlobby4 visual identity assets.
It stores reusable artworks in web-ready formats and project-level exports
used by README files, social cards, and organization pages.

## Directory responsibilities

- `project/assets/`: Editable source files
- `project/repo/`: Github repository-specific exports

## Naming Conventions

1. Use only lowercase letters, numbers and dashes.
2. Don't use spaces in file names.
3. Keep names stable after publication; add new files instead of renaming.
4. Use lowercase kebab style consistently within each folder.
5. If the asset is seasonal provide the year as a prefix.
6. If the asset was made by an outside contributor, provide the author as a prefix.

Recommended example pattern for file names:

```text
[<year>][-<author>][-<name>][-<variant>][-<size>].<ext>
```

## Documentation

Keep asset-generation notes close to the asset family (for example,
`project/assets/logos/nlobby4/info.txt`).
