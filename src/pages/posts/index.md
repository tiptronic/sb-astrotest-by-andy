---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Cool from '../../components/Author.astro'
title: Hello Andy in index.md!
publishDate: 12 Sep 2021
name: Nate Moore
value: 128
description: Just a Hello Andy Post!
---

<Cool name={frontmatter.name} href="https://twitter.com/n_moore" client:load />

This is so cool!

Do variables work {frontmatter.value + frontmatter.value}?

```javascript
// Example JavaScript

const x = 7;
function returnSeven() {
  return x;
}

```
