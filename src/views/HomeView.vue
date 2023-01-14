<template>
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