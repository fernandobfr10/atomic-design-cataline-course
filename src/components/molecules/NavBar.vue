<template>
  <nav class="nav-bar">
    <NavItem text="Serviços" to="/services" />
    <NavItem text="Sobre mim" to="/about" />
    <NavItem text="Cases" to="/cases" />
    <NavItem text="Contato" to="/contact" />
  </nav>
</template>

<script lang="ts">
import { NavItem } from '@/components/atoms'

import { defineComponent } from 'vue'
export default defineComponent({
  name: 'NavBar',
  components: {
    NavItem
  }
})
</script>

<style lang="scss" scoped>
.nav-bar {
  width: max-content;
  display: grid;
  grid-auto-flow: column;
  gap: 0 2rem;
}
</style>
