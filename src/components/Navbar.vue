<template>
  <div>
    <nav class="navbar" role="navigation" aria-label="main navigation">
    <div class="navbar-brand">
      <a class="navbar-item" href="/">
        PAY AND KEEP
      </a>
      <a role="button" class="navbar-burger" :class="{ 'is-active': navbarBurgerIsActive }" @click="navbarBurgerIsActive = !navbarBurgerIsActive" aria-label="menu" aria-expanded="false">
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
        <span aria-hidden="true"></span>
      </a>
    </div>
  </nav>
  </div>
</template>

<script>
export default {
  name: 'Navbar',
  data () {
    return {
      navbarBurgerIsActive: false
    }
  }
}
</script>
