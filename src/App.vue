<template>
  <main class="m-6">
  <MenuBar />
  <HomePage />
  <FooterBar />
</main>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import MenuBar from './components/MenuBar.vue';
import HomePage from './components/HomePage.vue';
import FooterBar from './components/FooterBar.vue';

export default defineComponent({
  name: 'App',
  components: {
    MenuBar,
    HomePage,
    FooterBar
  }
});
</script>

<style>

</style>
