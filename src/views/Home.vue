<template>
  <div class="home">
    
    <Zhinan />

    <Abroad />
  </div>
</template>

<script>
// @ is an alias to /src
import Abroad from '@/views/abroad/abroad.vue'
import Zhinan from '@/views/zhinan/index.vue'
export default {
  name: 'Home',
  components: {
    Abroad,
    Zhinan
  }
}
</script>
