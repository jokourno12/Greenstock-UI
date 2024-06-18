<template>
    <div>
      <Navigation />
      <div style="height: 50vh;">
        <Nuxt />
      </div>
      <Footer />
    </div>
</template>
  
<script lang="ts">
import Vue from 'vue';
import Navigation from '../components/Navigation.vue';
import Footer from '../components/Footer.vue';

export default Vue.extend({
    name: 'Default',
    components: {
        Navigation,
        Footer
    }
});
</script>
  
<style>
  /* Tambahkan CSS khusus untuk tata letak ini */
</style>
  