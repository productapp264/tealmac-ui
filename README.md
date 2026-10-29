# tealmac UI

Accessible React components, blocks, templates, charts and themes for [shadcn/ui](https://ui.shadcn.com) and Tailwind CSS v4.

**Site:** https://ui.tealmac.com

This repository is for **bug reports, item requests and docs problems**. The components themselves are installed from the tealmac UI registry with the shadcn CLI, not from this repository.

## Install a free item

```bash
npx shadcn@latest add https://ui.tealmac.com/r/login-01.json
```

Or add the namespace once to `components.json`:

```json
{
  "registries": {
    "@tealmac": "https://ui.tealmac.com/r/{name}.json"
  }
}
```

then `npx shadcn@latest add @tealmac/login-01`.

## Pro

Pro items install from a private registry with your licence key. See [Set up Pro](https://ui.tealmac.com/docs/guides/pro) and [Pricing](https://ui.tealmac.com/pricing).

## For coding agents

tealmac UI has an MCP server, so your coding agent can search the catalogue and get the right install command: https://ui.tealmac.com/mcp-server

## Report a problem

- [Bug report](../../issues/new?template=bug.yml): something is broken in an item or on the site.
- [Item request](../../issues/new?template=request.yml): a component, block or template you would like to see.
- [Docs problem](../../issues/new?template=docs.yml): something in the docs is wrong or unclear.

Licence keys, billing and anything private: email **hello@tealmac.com**. Please do not post licence keys in issues.

## Licence

Free items are free to use in personal and commercial projects. Pro items are covered by the [Pro licence](https://ui.tealmac.com/license/pro). See [License](https://ui.tealmac.com/license).

shadcn/ui is a trademark of its owner; tealmac UI is built on shadcn/ui and is not affiliated with it.
