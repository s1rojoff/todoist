<template>
  <ul>
    <li>Features</li>
    <li>Templates</li>
    <li>For Teams</li>
    <li>
        Resources
        <i class="fa-solid fa-chevron-down"></i>    
    </li>
  </ul>
</template>

<script>
export default {
    name: 'NavItem'
}
</script>

<style scoped>
 ul{
    list-style: none;
    display: flex;
    margin-left: -250px;
 }
li{
    /* margin-left: 20px; */
    font-size: 16px;
    font-family: 'Poppins', sans-serif;
    background: #fff;
    font-size: 16px;
    border-radius: 10px;
    padding: 10px 15px;
}
li:hover{
    background: #F0F0F0;
    font-size: 16px;
    border-radius: 10px;
    padding: 10px 15px;

}
</style>