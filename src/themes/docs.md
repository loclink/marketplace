---
title: Docs Themes
icon: book
order: 1
---

<ProjectPanel v-for="item in config" v-bind="item" />

<script setup lang="ts">
import config from '@docs-theme-config'
</script>
