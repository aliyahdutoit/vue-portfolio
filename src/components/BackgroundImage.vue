
<template>
    <div class="home">
    <div data-aos="zoom-in" data-aos-duration="3000" >
<h1>Aliyah du Toit</h1>
<h3>Welcome to my Website</h3>
    </div>
</div>
</template>

<script>
import AOS from "aos";
    export default {
        mounted() {
        AOS.init();
    },
        name: 'BackgroundImage'
    }
</script>

<style>
.home {
    min-height: 58vh;
}
</style>