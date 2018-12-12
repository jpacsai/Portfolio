<template>
  <div class="home">
    <!-- <img class="placeholder" :src="placeholder" alt="temporary placeholder" /> -->
    <svgPicture />
  </div>
</template>

<script lang="ts">
// import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src
import svgPicture from '@/components/Picture.vue'

export default {
  name: 'home',
  data () {
    return {
      placeholder: require('../assets/temporaryplaceholder.jpg'),
    }
  },
  components: {
    svgPicture
  },
};
</script>
