<template>
  <h1 class="text"  :style="`color:${color} ; font-size:${size}px`">
    <slot>Achive peace of mind <br> with TodoIst</slot>
  </h1>
</template>

<script>
export default {
    name: "FoText",
    props:{
        color : String,
        size : String
    }
}
</script>

<style lang="scss" scoped>
  .text{
    font-size: 40px;
  }
</style>