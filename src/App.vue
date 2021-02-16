<template>
  <div class="component">
    <SearchForm />
  </div>
</template>

<script lang="ts">
import { SearchForm } from '@/components/molecules'

import { defineComponent } from 'vue'

export default defineComponent({
  name: 'App',
  components: {
    SearchForm
  }
})
</script>
