<template>
  <header>
    <div class="logo">
      <p>let's <span class="bold">UX</span> it</p>
    </div>
    <div class="menu">
      <Menu />
    </div>
  </header>
</template>

<script>
import Menu from './Menu'
export default {
  name: 'Header',
  components: { Menu },
}
</script>

<style scoped>
header {
  display: flex;
  justify-content: space-between;
}
.bold {
  font-family: 'Inter Bold';
}
</style>
