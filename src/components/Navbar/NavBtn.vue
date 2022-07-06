<template>
  <button class="btn" :style = "`background-color : ${color};color:${text}`">
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
        text :  String
    }
}
</script>

<style lang="scss" scoped>
 .btn{
    border: none;
    outline: none;
    padding: 12px 15px;
    font-size: 17px;
    border-radius: 10px;
    margin-right: 10px;

    &:hover{
        opacity: 0.9;
    }
 }
</style>