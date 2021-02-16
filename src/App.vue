<template>
  <div class="component">
    <Service
      title="Front-End"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Quos minus exercitationem, voluptas neque repellat voluptates ipsa vel aut labore error blanditiis amet laborum deleniti iste obcaecati nemo perferendis at necessitatibus?"
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import { Service } from '@/components/molecules'

export default defineComponent({
  name: 'App',
  components: {
    Service
  }
})
</script>
