# NorthAxium Data docs

This repository contains the Mintlify documentation site for NorthAxium Data.

## Local development

Install the Mintlify CLI if you do not already have it:

```bash
npm i -g mint
```

Start the local preview from this directory:

```bash
mint dev
```

The preview runs at `http://localhost:3000`.

## Validation

Run these checks before shipping docs changes:

```bash
mint validate
mint broken-links
mint a11y
```

## Repo conventions

- Site-wide configuration lives in `docs.json`
- Global styling overrides live in `custom.css`
- Content pages are MDX files with YAML frontmatter
- Prefer Mintlify-native config and components before adding custom CSS

## References

- [Mintlify documentation](https://mintlify.com/docs)
