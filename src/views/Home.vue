<template>
  <div class="home">
    <img alt="Kataryna Logo" src="../assets/logo.png">
    <Temp />
  </div>
</template>

<script>
// @ is an alias to /src
import Temp from '@/components/Temp.vue'

export default {
  name: 'Home',
  components: {
    Temp
  }
}
</script>
