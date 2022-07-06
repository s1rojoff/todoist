<template>
  <div class="row">
    <slot></slot>
  </div>
</template>

<script>
export default {
    name:'SecondSection'
}
</script>

<style scoped>
  .row{
    display: flex;
    align-items: center;
    /* margin-top: 100px; */
    margin: 100px auto;
  }
</style>