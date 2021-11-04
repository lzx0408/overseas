<template>
  <div class="home">
    
    <Abroad />
  </div>
</template>

<script>
// @ is an alias to /src
import Abroad from '@/views/abroad/abroad.vue'

export default {
  name: 'Home',
  components: {
    Abroad
  }
}
</script>
