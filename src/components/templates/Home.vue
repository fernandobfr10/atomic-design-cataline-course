<template>
  <Container class="home">
    <Header />
    <Presentation />
    <Services />
  </Container>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

import { Container } from '@/components/bosons'
import { Header, Presentation, Services } from '@/components/organisms'

export default defineComponent({
  name: 'Home',
  components: {
    Container,
    Header,
    Presentation,
    Services
  }
})
</script>

<style lang="scss" scoped>
.home {
  margin: 5rem auto;
  display: grid;
  gap: 5rem;
}
</style>
