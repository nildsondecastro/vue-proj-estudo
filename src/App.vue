<template>
  <PrimeiroComponente />
  <p>O dado de app é {{ testando }}</p>
  <life-cycle />
  <Pessoa />
</template>

<script>

import PrimeiroComponente from './components/PrimeiroComponente.vue'
import LifeCycle from './components/LifeCycle.vue'
import Pessoa from './components/Pessoa.vue'

export default {
  name: 'App',
  components: {
    PrimeiroComponente,
    LifeCycle,
    Pessoa
  },
  data () {
    return {
      testando: 'Teste'
    }
  }
}
</script>
