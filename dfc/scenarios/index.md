---
title: 'Scenarios'
excerpt: 'Dropfleet Commander scenarios.'
position: 6
---
# {{ $frontmatter.title }}

<script setup>
  import { data as pages } from '/documents.data'
  const slug = '/en/dfc/scenarios/'
  const filteredPages = pages.filter(page => page?.href.indexOf(slug) > -1
      && page?.href.indexOf('index.html') < 0
      && !page?.href.endsWith('/'))
    .sort((a, b) => a.position - b.position)
</script>

<CategoryCardsContainer :pages="filteredPages" />
