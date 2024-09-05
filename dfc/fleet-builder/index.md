---
title: 'Dropfleet Builder'
excerpt: 'Dropfleet Commander Fleet Builder.'
position: 10
---

# {{ $frontmatter.title }}

<script setup>
  import { data as api } from '/en.dfc.api.data'
  const view = 'full'
  const name = 'Toulon'
</script>

You can build your own Dropfleet Commander fleet using [TTCombat's Fleet Builder](https://dropfleetcommander.com/builder).

## Experimental

In the meantime, while we're working in our own fleet builder, you can use these templates to print your fleet:

<ShipCard :api="api" :name="name" :view="view" />
