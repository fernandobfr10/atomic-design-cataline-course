<template>
  <div class="services">
    <Service
      title="Front end"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio optio repellendus eaque nisi illum eum cum libero aperiam. Nesciunt esse error facere inventore placeat explicabo aliquam ipsam, suscipit consequatur mollitia.."
    />
    <Service
      title="Back end"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio optio repellendus eaque nisi illum eum cum libero aperiam. Nesciunt esse error facere inventore placeat explicabo aliquam ipsam, suscipit consequatur mollitia.."
    />
    <Service
      title="Manutenção"
      description="Lorem ipsum dolor sit amet consectetur adipisicing elit. Odio optio repellendus eaque nisi illum eum cum libero aperiam. Nesciunt esse error facere inventore placeat explicabo aliquam ipsam, suscipit consequatur mollitia.."
    />
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

import { Service } from '@/components/molecules'

export default defineComponent({
  name: 'Services',
  components: {
    Service
  }
})
</script>

<style lang="scss" scoped>
.services {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 5rem;
}
</style>
