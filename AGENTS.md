# Formbrew documentation instructions

## About this project

- This is Formbrew's public documentation site built on Mintlify
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- API specifications are loaded from the staging URLs configured in `docs.json`

## Terminology

- Use "public form token" for the publishable token used by frontend integrations
- Use "Management API" rather than "App API"
- Use "allowed origin" for an exact website scheme, hostname, and optional port
- Use uppercase enum values only when referring to API values; use sentence case for UI labels

## Style preferences

- Use active voice and second person ("you")
- Keep sentences concise; use one idea per sentence
- Use sentence case for headings
- Bold UI elements, for example **Settings**
- Use code formatting for file names, commands, paths, and code references

## Content boundaries

- Document only shipped behavior and clearly label current limitations
- Do not publish internal architecture, deployment, security-planning, or roadmap documents
- Do not add Management API authentication setup until external credentials are available
- Do not add checked-in OpenAPI files; Mintlify reads the published specifications directly
- Use staging API URLs until production API documentation is available
