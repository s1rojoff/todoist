<template>
  <div class="text">
    <p class="text_lg">Organize your <br> work and life , finally.</p>
    <p class="text_sm">
        Become focused, organized, and calm with Todoist. <br>
        The worlds #1 task manager and to-do list app.
    </p>
    <NavBtn color="#E44232" text="#fff"/>
  </div>
</template>

<script>
import NavBtn from '../Navbar/NavBtn.vue';
export default {
    name: 'HeaderText',
    components: { NavBtn }
}
</script>

<style lang="scss" scoped>
.orange{
    background: #E44232;
    color: #fff;
  }
.text{
    text-align: center;
    font-family: 'Poppins', sans-serif;
    line-height: 1.2;
    margin-top: 115px;
&_lg{
    font-size: 50px;
    font-weight: 600;
}
&_sm{
    // margin-top: -35px;
    font-size: 20px;
    font-weight: 300;
    margin-bottom: 20px;
}
}
</style>