---
title: 'Core rules'
excerpt: 'Dropfleet Commander core rules.'
position: 4
---
# Core rules

<script setup>
  import { data as pages } from '/documents.data'
  const slug = '/en/dfc/core-rules/'
  const filteredPages = pages.filter(page => page?.href.indexOf(slug) > -1 && page?.href.indexOf('index.html') < 0)
    .sort((a, b) => a.position - b.position)
</script>

<CategoryCardsContainer :pages="filteredPages" />
