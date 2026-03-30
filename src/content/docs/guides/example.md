---
title: Example Guide
description: A guide in my new Starlight docs site.
---


import { Card, CardGrid, Callout } from '@astrojs/starlight/components';

# Introduction

Guides lead a user through a specific task they want to accomplish, often with a sequence of steps. Writing a good guide requires thinking about what your users are trying to do.

<Callout type="info" icon="info">
	This is a sample guide using <strong>Starlight</strong> and AstroJS built-in components.
</Callout>

## Prerequisites

- Node.js and npm installed
- Basic familiarity with Markdown
- Astro and Starlight set up (see project README)

## Step 1: Create a New Page

<CardGrid>
	<Card title="Add a Markdown file" icon="add-document">
		Create a new <code>.md</code> or <code>.mdx</code> file in <code>src/content/docs/guides/</code>.
	</Card>
	<Card title="Write Frontmatter" icon="pencil">
		Add <code>title</code> and <code>description</code> in the frontmatter block at the top.
	</Card>
</CardGrid>

## Step 2: Use Components

You can use built-in Starlight components like <code>Card</code>, <code>CardGrid</code>, and <code>Callout</code> in your MDX files to enhance your docs.

<Callout type="tip" icon="star">
	Try combining components for more engaging documentation!
</Callout>

## Example Code Block

```js
// Example JavaScript code
console.log('Hello, Starlight!');
```

## Next Steps

- Explore more Starlight components in the [official docs](https://starlight.astro.build/reference/components/)
- Customize your guide with images, links, and more

## Further Reading

- Read [about how-to guides](https://diataxis.fr/how-to-guides/) in the Diátaxis framework
