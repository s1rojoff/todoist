<template>
  <nav>
    <slot></slot>
  </nav>
</template>

<script>
export default {
    name: 'Navbar'
}
</script>

<style scoped>
    nav{
        display: flex;
        align-items: center;
        padding: 10px 120px;
        justify-content: space-between;
    }
</style>