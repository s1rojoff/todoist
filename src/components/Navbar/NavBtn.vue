<template>
  <button :style="`background:${color}; color:${text}`" class="btn">
    <slot>
        Start for free
    </slot>
  </button>
</template>

<script>
export default {
    name:'NavBtn',
    props:{
      color: String,
      text: String
    }
}
</script>

<style lang="scss">
 .btn{
    border: none;
    outline: none;
    padding: 12px 15px;
    font-size: 17px;
    border-radius: 10px;
    margin-right: 10px;
 }
</style>