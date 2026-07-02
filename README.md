# Ambient Docs

This is the Mintlify documentation site for Ambient.

## Pages

- `index.mdx` is the docs home page.
- `quickstart.mdx` is the installation guide.
- `introduction.mdx` is the first-run guide.
- `guides/` contains the memory, integrations, and handoffs guides.

## Development

Install the [Mintlify CLI](https://www.npmjs.com/package/mint) to preview changes locally:

```bash
npm i -g mint
```

Run the preview from this directory, where `docs.json` lives:

```bash
mint dev
```

View your local preview at `http://localhost:3000`.

## Publishing changes

Mintlify deploys changes from the connected GitHub repository. The primary download button is configured in `docs.json`.
