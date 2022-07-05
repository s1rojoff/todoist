<template>
    <div  class="two-content">
        <slot></slot>
    </div>
</template>

<script>
export default {
    name:"FlexWrap"
}
</script>

<style lang="scss" scoped>
    .two-content{
        margin : 0 auto;
        width: 80%;
          display: flex;
         align-items: center;
         justify-content: space-between;
         flex-direction: row;
        padding: 0 3rem;
        border-bottom: 1px solid grey
    }
</style>