<template>
  <button :class="color" class="btn">
    <slot>
        Start for free
    </slot>
  </button>
</template>

<script>
export default {
    name:'NavBtn',
    props:['color']
}
</script>

<style lang="scss">
 .btn{
    border: none;
    outline: none;
    padding: 12px 15px;
    font-size: 16px;
    border-radius: 10px;
    margin-right: 10px;
 }
</style>