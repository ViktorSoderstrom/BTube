<template>
  <div class="home">
    Bertil
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import HelloWorld from '@/components/HelloWorld.vue' // @ is an alias to /src

export default Vue.extend({
  name: 'Home',
  data () {
    return {
      backgroundURL: '../assets/background.jpg'
    }
  },
  components: {
  }
})
</script>
