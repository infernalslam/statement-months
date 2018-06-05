<template>
  <div>
    <navbar-menu></navbar-menu>
    <card color="background: linear-gradient(30deg,#8ae48d,#16be77);"></card>
    <card color="background: linear-gradient(30deg,#2074ff,#601fff);"></card>
    <card color="background: linear-gradient(30deg,#ff4657,#d50a65)"></card>
  </div>
</template>

<script>
import NavbarMenu from '@/components/Navbar'
import Card from '@/components/Card'
export default {
  name: 'index',
  components: {
    NavbarMenu,
    Card
  }
}
</script>

<style scoped>
</style>
