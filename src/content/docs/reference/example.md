---
title: Example Reference
description: A reference page in my new Starlight docs site.
---

import { Card, CardGrid } from '@astrojs/starlight/components';

Reference pages are ideal for outlining how things work in terse and clear terms.
Less concerned with telling a story or addressing a specific use case, they should give a comprehensive outline of what you're documenting.

<CardGrid>
	<Card title="Quick note" icon="information-circle">
		MDX components from Astro make it easy to build reusable UI blocks inside docs.
	</Card>
	<Card title="Code example" icon="code">
		You can mix Markdown and interactive components in the same file.
	</Card>
</CardGrid>

## Getting started

1. Install the package:

```bash
npm install @myorg/starlight-docs
```
## Get started
2. Create a content file under `src/content/docs`.

3. Add metadata and structure.

4. Start the dev server:

```bash
npm run dev
```

## API overview

### `loadDocs(options)`

- `options.path` (string): directory to load markdown files from.
- `options.locale` (string, optional): locale code for i18n.

Returns a document tree used by the site router.

### `renderPage(page)`

- `page.title` (string): page title.
- `page.content` (string): HTML content.

Renders the page with your theme and table of contents.

1. `page.title` (string): page title.
2. `page.content` (string): HTML content.
3. `page.metadata` (string): HTML content.
- If your docs are not showing, ensure the `src/content` folder is included in `content.config.ts`.
- If a page is missing metadata, add `title` and `description` at the top of the file.

## Further reading

- Read [about reference](https://diataxis.fr/reference/) in the Diátaxis framework
