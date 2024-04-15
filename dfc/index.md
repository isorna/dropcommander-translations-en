---
title: 'Dropfleet Commander'
excerpt: 'Dropfleet Commander game rules.'
position: 0
---

# Dropfleet Commander

<script setup>
  import { data as pages } from '/documents.data'
  const slug = '/en/dfc/'
  const filteredPages = pages.filter(page => page?.href.indexOf(slug) > -1)
  const selectedPages = [
    filteredPages.find(page => page.href == `${slug}contents.html`),
    filteredPages.find(page => page.href == `${slug}earth-2673.html`),
    filteredPages.find(page => page.href == `${slug}the-basics/`),
    filteredPages.find(page => page.href == `${slug}core-rules/`),
    filteredPages.find(page => page.href == `${slug}building-your-fleet.html`),
    filteredPages.find(page => page.href == `${slug}scenarios/`),
    filteredPages.find(page => page.href == `${slug}special-rules.html`),
    filteredPages.find(page => page.href == `${slug}glossary.html`),
  ]
</script>

<CategoryCardsContainer :pages="selectedPages" />
