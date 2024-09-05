---
title: 'Force Builder'
excerpt: 'Dropzone Commander Force Builder.'
position: 9
---

# {{ $frontmatter.title }}

<script setup>
  import { data as api } from '/en.dzc.api.data'
  const view = 'full'
  const name = 'Resistance Fighters'
</script>

You can build your own Dropzone Commander army using [TTCombat's Force Builder](https://dropzonecommander.com/forcebuilder).

## Experimental

In the meantime, while we're working in our own force builder, you can use these templates to print your army:

<TroopCard :api="api" :name="name" :view="view" />
