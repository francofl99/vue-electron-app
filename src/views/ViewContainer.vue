<template>
<div class="flex flex-row">
    <dashboard/>
</div>

</template>

<script lang="ts">
import { defineComponent } from 'vue'
import Dashboard from '../components/Dashboard.vue'

export default defineComponent({
  name: 'ViewContainer',

  components: {
    Dashboard
  }
})
</script>

<style>

</style>
