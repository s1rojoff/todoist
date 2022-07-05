<template>
  <div>
    <div class="first-imgs">
        <img class="left" src="@/assets/img/first-right.webp" alt="">
        <img class="center" src="@/assets/img/first-center.webp" alt="">
        <img class="right" src="@/assets/img/first-left.webp" alt="">
    </div>
   <img class="back" src="@/assets/img/first-back.webp" alt="">
  </div>
</template>

<script>
export default {
    name: 'FirstContent'
}
</script>

<style scopeed>
    .back{
        width: 100%;
        padding: 0;
    }
    .left{
        width: 23%;
        margin-top: 180px;
        padding: 0;
    }
    .right{
        margin-left: -200px;
         width: 25%;
        margin-top: 260px;
        padding: 0;
    }
    .center{
        width: 75%;
        z-index: 10;
        margin-left: -110px;
        margin-top: 45px;
    }
    .first-imgs{
        display: flex;
        align-items: center;
        margin-top: -25px;
    }
</style>