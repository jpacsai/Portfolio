<template>
  <div class="home">
    <img class="placeholder" :src="placeholder" alt="temporary placeholder" />
  </div>
</template>

<script lang="ts">
// import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

export default {
  name: 'home',
  data () {
    return {
      placeholder: require('../assets/temporaryplaceholder.jpg'),
    }
  },
  components: {},
};
</script>
