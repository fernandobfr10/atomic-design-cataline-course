<template>
  <Home />
</template>

<script lang="ts">
import { defineComponent } from 'vue'

import { Home } from '@/components/templates'

export default defineComponent({
  name: 'App',
  components: { Home }
})
</script>

<style lang="scss" scoped>
.component {
  margin: 5rem;
}
</style>
