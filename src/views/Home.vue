<template>
  <div class="home">
    <Plan />
    <Zhinan />

    <Abroad />
    <Usa />
    <Usa />
    <Usa />
    <Usa />
  </div>
</template>

<script>
// @ is an alias to /src
import Abroad from '@/views/abroad/abroad.vue'
import Zhinan from '@/views/zhinan/index.vue'
import Plan from '@/views/plan/index.vue'
import Usa from '@/views/usa/index.vue'
export default {
  name: 'Home',
  components: {
    Abroad,
    Zhinan,
    Plan,
    Usa
  }
}
</script>
