<template>
  <div class="about">
    <div class="about-container">
      <img :src="selfie" alt="photo of Judit" />
      <section>
        <p>Lorem ipsum dolor sit amet, vim ut adhuc postulant. Nec integre laoreet in, ut ubique ridens pro. Ad mel iudico insolens mediocrem. Ut vim vocent ancillae rationibus, no eos illud impedit.</p>
        <p>Denique minimum mel at. Adhuc porro deterruisset id pri, id discere sanctus civibus qui, id sit choro dolor habemus. Justo accusam pro eu. Viris aperiri ex per, et mundi prompta volumus per, eum ut lobortis dissentiunt. Vim iisque mentitum deseruisse et, id utamur inciderint sed. Dolor quaeque feugiat nec at, hinc rebum percipitur an his.</p>
      </section>
    </div>
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
