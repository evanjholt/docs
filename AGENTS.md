# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Terminology

- Use "NorthAxium Data" for the product name
- Use "dataset" for a data domain such as contracts, grants, or lobbying
- Use "API key" for authentication credentials
- Use "MCP server" when referring to the Model Context Protocol integration
- Use "page" or "documentation page", not "article"
- Use "endpoint" for REST routes and "tool" for MCP actions

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references
- Prefer root-relative internal links such as `/quickstart`
- Keep API reference language concrete and operational
- Favor built-in Mintlify components over custom markup
- Use `docs.json` for branding, navigation, API config, and theme settings before reaching for `custom.css`
- Use `custom.css` only for stable Mintlify selectors or documented identifiers
- Preserve the existing NorthAxium visual identity when doing standards cleanup
- Avoid undocumented Mintlify config keys unless a current Mintlify release requires them and that use is verified in repo context

## Content boundaries

- Document public APIs, guides, authentication, coverage, and MCP setup
- Do not document internal admin tools or internal-only operational workflows
- Do not add speculative product claims or roadmap statements unless the page already commits to them
