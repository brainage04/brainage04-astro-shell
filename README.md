# @brainage04/astro-shell

Shared Astro shell components and base styles for brainage04 websites.

## Install

```bash
npm install @brainage04/astro-shell
```

## Components

```astro
---
import SiteLayout from '@brainage04/astro-shell/components/SiteLayout.astro';
import TerminalPanel from '@brainage04/astro-shell/components/TerminalPanel.astro';
---
```

## Exports

- `@brainage04/astro-shell/components/PageHeader.astro`
- `@brainage04/astro-shell/components/SiteLayout.astro`
- `@brainage04/astro-shell/components/SiteHeader.astro`
- `@brainage04/astro-shell/components/SiteFooter.astro`
- `@brainage04/astro-shell/components/TerminalPanel.astro`
- `@brainage04/astro-shell/global.css`

## Release

Manual release:

```bash
npm version patch
npm publish --access public
git push
git push --tags
```

GitHub release publishing is also wired through `.github/workflows/publish.yml`; it requires an `NPM_TOKEN` repository secret with publish permission.
