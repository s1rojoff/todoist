<template>
  <div id="app">
    <Navbar>
      <NavLogo/>
      <NavItem/>
      <div>
        <NavBtn color="light">Log in</NavBtn>
        <NavBtn color="orange"/>
      </div>
    </Navbar>
  </div>
</template>

<script>
import NavLogo from '@/components/Navbar/NavLogo.vue';
import NavItem from './components/Navbar/NavItem.vue';
import NavBtn from './components/Navbar/NavBtn.vue';
import Navbar from './components/Navbar/Navbar.vue';
export default {
    components: { NavLogo, NavItem, NavBtn, Navbar }
}
</script>

<style>
  .orange{
    background: #E44232;
    color: #fff;
  }
  .light{
    background: white;
  }
  .light:hover{
    background: #F0F0F0;
  }
</style>