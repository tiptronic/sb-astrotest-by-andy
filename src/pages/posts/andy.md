---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Cool from '../../components/Author.astro'
title: Hello Andy Post!
publishDate: 25.03.2022
name: Andy Fuchs
value: 128
description: Just a Hello Andy Fuchs!
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
