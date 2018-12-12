<template>
  <div class="view about">
    <img :src="selfie" alt="photo of Judit" />
  </div>
</template>

<script lang="ts">
// import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

export default {
  name: 'about',
  data () {
    return {
      selfie: require('../assets/selfie.jpg'),
    }
  },
  components: {},
};
</script>
