<template>
   <Header />
   <RouterView  />
</template>

<script>
import Header from "../components/Header.vue";

export default {
   components: {
      Header,
   },
};
</script>

<style>
   @import '../style/reset.css';
   @import '../style/font.css';
   @import '../style/variables.css';
   @import '../style/style.css';
</style>