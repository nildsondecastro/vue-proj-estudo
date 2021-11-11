<template>
  <PrimeiroComponente />
  <p>O dado de app é {{ testando }}</p>
  <life-cycle />
</template>

<script>

import PrimeiroComponente from './components/PrimeiroComponente.vue'
import LifeCycle from './components/LifeCycle.vue'

export default {
  name: 'App',
  components: {
    PrimeiroComponente,
    LifeCycle
  },
  data () {
    return {
      testando: 'Teste'
    }
  }
}
</script>
