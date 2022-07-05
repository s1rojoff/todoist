<template>
    <div>
        <img :src="img" alt="flower">
    </div>
    
</template>

<script>
export default {
    name : "VImage",
    props : {
        img: String
    }

}
</script>

<style>

</style>