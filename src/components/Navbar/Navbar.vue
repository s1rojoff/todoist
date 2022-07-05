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

<style>
    nav{
        display: flex;
        align-items: center;
        padding: 0 100px;
        justify-content: space-between;
    }
</style>