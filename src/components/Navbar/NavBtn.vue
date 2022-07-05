<template>
<<<<<<< HEAD
  <button class="btn" :style = "`background-color : ${color};color:${text}`">
=======
  <button :style="`background:${color}; color:${text}`" class="btn">
>>>>>>> 0d23b495e802cee27fdeec04b7236af4c6366fde
    <slot>
        Start for free
    </slot>
  </button>
</template>

<script>
export default {
    name:'NavBtn',
    props:{
<<<<<<< HEAD
        color: String,
        text :  String
=======
      color: String,
      text: String
>>>>>>> 0d23b495e802cee27fdeec04b7236af4c6366fde
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
<<<<<<< HEAD

    &:hover{
        opacity: 0.9;
    }
 }

=======
 }
>>>>>>> 0d23b495e802cee27fdeec04b7236af4c6366fde
</style>