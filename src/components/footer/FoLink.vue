<template>
 <ul>
    <li v-for="item in items" :key="item" >
        <a href="#">{{item}}</a>
    </li>
 </ul>
</template>

<script>
export default {
    name :"FoLink",
    props:{
        items: Array || Object
    }
}
</script>

<style lang="scss" scoped>
    li{
        list-style: none;
        color: grey;
        line-height: 30px;
       
        a{
            text-decoration: none;
            color: grey;
             &:hover{
            border-bottom:1px solid grey ;
            
        }
        }
    }
</style>