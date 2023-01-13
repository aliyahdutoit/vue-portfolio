<template>
<!-- <div class="home">
  <h1>Aliyah du Toit</h1>
  <h3>Welcome to my Website</h3>
</div> -->
<BackgroundImage/>
</template>
<script>
// @ is an alias to /src
import BackgroundImage from '@/components/BackgroundImage.vue';

export default {
  name: 'HomeView',
  components: {
   BackgroundImage
  }
}
</script>
<style>
template{
background-color: purple;
}
.home {
  padding: 300px;
}
h1 {
  font-weight: bolder;
}
</style>