<template>
  <h1>
    Oi {{ nome }}
  </h1>
</template>

<script>
export default {
  name: 'LifeCycle',
  data () {
    return {
      nome: 'Ainda não sei'
    }
  },
  created () {
    setTimeout(() => {
      this.nome = 'created - setTimeout 1s'
    }, 1000)
  },
  mounted () {
    setTimeout(() => {
      this.nome = 'mounted - setTimeout 3s'
    }, 3000)
  }
}
</script>
