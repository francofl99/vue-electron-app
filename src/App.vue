<template>
  <div class="w-screen h-screen">
    <MainView />
  </div>

</template>

<script lang="ts">
import { defineComponent } from 'vue'
import MainView from './views/MainView.vue'

export default defineComponent({
  name: 'App',

  components: {
    MainView
  }
})
</script>

<style>

</style>
