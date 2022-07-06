<template>
  <div id="app">
    <Navbar>
      <NavLogo/>
      <NavItem/>
      <div>
        <NavBtn color="F0F0F0">Log in</NavBtn>
        <NavBtn color="#E44232" text="#fff"/>
      </div>
    </Navbar>
    <HeaderText/>
    <FirstContent/>
    <LogosIcons/>
    <SecondSection>
      <SecondText/>
      <SecondImg/>
    </SecondSection>
    <Footer />
  </div>
</template>

<script>
import NavLogo from '@/components/Navbar/NavLogo.vue';
import NavItem from '@/components/Navbar/NavItem.vue';
import NavBtn from '@/components/Navbar/NavBtn.vue';
import Navbar from '@/components/Navbar/Navbar.vue';
import HeaderText from '@/components/FirstSection/HeaderText.vue';
import FirstContent from '@/components/FirstSection/FirstContent.vue'
import LogosIcons from '@/components/FirstSection/LogosIcons.vue'
import SecondSection from './components/SecondSection/SecondSection.vue';
import SecondText from './components/SecondSection/SecondText.vue';
import SecondImg from './components/SecondSection/SecondImg.vue'
import Footer from '@/components/Footer';
export default {
    components: {
    NavLogo,
    NavItem,
    NavBtn,
    Navbar,
    HeaderText,
    FirstContent,
    LogosIcons,
    SecondSection,
    SecondText,
    SecondImg,
    Footer
}
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
