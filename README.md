# Formbrew documentation

This repository contains Formbrew's public Mintlify documentation. `docs.json` at the repository root defines the Dashboard, Frontend, Public API, and Management API sections.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint):

```bash
npm i -g mint
```

Preview the site from this repository root:

```bash
mint dev
```

The local preview is available at `http://localhost:3000`.

## API specifications

Mintlify loads the Public API and Management API specifications from the staging API URLs configured in `docs.json`. The specifications do not live in this repository.

## Validate changes

```bash
mint validate
mint broken-links
```

## Deploy

Connect this repository to Mintlify. Because `docs.json` is at the repository root, do not configure a documentation subdirectory.
